# System-Admin-Helper
- System-Admin-Helper is a simple GUI that help Linux administrator to manage there users and groups based on a collection of shell script files The scripts use whiptail to provide an interactive user interface.


## Features
The following features are available in System-Admin-Helper:

- Add user
- Delete user
- Add group
- Delete group
- List users
- List groups
- Modify user
## Usage
To use System-Admin-Helper, simply run the desired script from the command line. For example, to add a user, run menu script:-
```
./menu
```
The script will prompt you for the necessary information using whiptail.

## Scripts
The following scripts are included in System-Admin-Helper:

- add_user - Adds a new user.
- add_group - Adds a new group.
- delete_user - Deletes an existing user.
- delete_group - Deletes an existing group.
- list_users - Lists all users.
- list_groups - Lists all groups.
- modify_user - Modifies an existing user based on your selection
# Prerequisite
- install whiptail to create more user-friendly interactive scripts
```
[damon@localhost ~]$ sudo dnf install newt
```
# GUI
https://github.com/mostafa-magdi/System-Admin-Helper/assets/129240702/c70f9d39-6f21-4f44-be65-38618a11aecd

# Conclusion
System-Admin-Helper is a useful collection of shell script files that can help Linux users manage users and groups. The scripts are easy to use and provide an interactive interface using whiptail
