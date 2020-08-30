### Get predictions for your dataset.
[Live Demo](https://ml-online.herokuapp.com/)
##### Current features:
- Drops all the columns with type "objects"
- If there are just 2 distinct values in a column, it replaces them with boolean
- Option to select from Logistic Regression, SVM, Linear Regression, Descision Tree.
- Return a csv file to download with all the columns and the predictions column back(in case the user wants specific columns back).

Running serever locally :
```
$ pipenv shell
$ chmod +x run_locally.sh
$ ./run_locally.sh 
```

If you install new pip library :
```
$ pip install name
$ rm requirements.txt
$ pip freeze > requirements.txt
```
