# This is the project for iii.
## Team: CB101 4th
### Modules:
1. state_code_cleaner<br>
This is a module for checking how many state codes in specific data, and it will check missing value at the same time.
You could run the commandline as below. To get a new and clear file in the same folder but the name with new tag, 'clr'.

>##### COMMAND LINE
>cd ./state_code_cleaner<br>
>python3 main.py [data in anywhere if you want]<br>

2. make_center<br>
Then we could use correct state code as row name to create a new dataframe. It will be added new tag '_range' in filename.

>##### COMMAND LINE
>cd ./make_center<br>
>python3 main.py [clean data]<br>
