# task-manager-api
base URL - https://something-need-to-do.herokuapp.com/

Create user
POST [https://something-need-to-do.herokuapp.com/users]

Login user
POST [https://something-need-to-do.herokuapp.com/users/login]

Logout user
POST [https://something-need-to-do.herokuapp.com/users/logout]

Logout all
POST [https://something-need-to-do.herokuapp.com/users/logoutAll]

Create task
POST [https://something-need-to-do.herokuapp.com/tasks]

Upload avatar
POST [https://something-need-to-do.herokuapp.com/users/me/avatar]

Read profile
GET [https://something-need-to-do.herokuapp.com/users/me]

Read avatar
GET [https://something-need-to-do.herokuapp.com/users/:id/avatar]

Read tasks
GET [https://something-need-to-do.herokuapp.com/tasks]

Read task
GET [https://something-need-to-do.herokuapp.com/tasks/:id]

Update user
PATCH [https://something-need-to-do.herokuapp.com/users/me]

Update task
PATCH [https://something-need-to-do.herokuapp.com/tasks/:id]

Delete user
DELETE [https://something-need-to-do.herokuapp.com/users/me]

Delete avatar
DELETE [https://something-need-to-do.herokuapp.com/users/me/avatar]

Delete task
DELETE [https://something-need-to-do.herokuapp.com/tasks/:id]
