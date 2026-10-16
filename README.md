# Experiment 9: Data Persistence

## Objective
To demonstrate data persistence in an Android application using SharedPreferences and SQLite Database.

## Part 1: SharedPreferences

SharedPreferences is used to store small amounts of data permanently in key-value form.

### Features
- Enter a name.
- Automatically save the name.
- Load the saved name.
- Clear the saved name.

### Result
The entered name is saved and can be loaded again after restarting the application.

## Part 2: SQLite Database

SQLite is a lightweight local database used to store structured data in Android applications.

### Features
- Enter Student Name.
- Enter Student Email.
- Add student record.
- View all student records.
- Clear all records.

### Database Fields

| Field | Type |
|---|---|
| ID | INTEGER PRIMARY KEY AUTOINCREMENT |
| Name | TEXT |
| Email | TEXT |

## Working

1. Enter a name in the SharedPreferences section.
2. The name is automatically saved.
3. Click LOAD NAME to retrieve the saved name.
4. Enter student name and email.
5. Click ADD STUDENT to save the record.
6. Click VIEW ALL to display all records.
7. Click CLEAR ALL to delete all records.

## Result

The experiment successfully demonstrates data persistence using SharedPreferences and SQLite Database.

## Conclusion

Data remains stored even after the application is closed and reopened. Thus, persistent local data storage in Android is successfully demonstrated.
