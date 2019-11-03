# devops-training-public

Exercise requirements:
1. docker account.
2. docker service installed on the host.

Exercise flow:
1. pull mongo version 4.0.4 container.
2. create new database inside the mongo container:
    - database data is in 'data.txt' file. 
    - database name: 'cr-db'.
    - collections name 'users'.
    - you can use mongo native commands inside the container or write code. 
3. export the database data from the container to the host:
    - write code to do that method.
4. manipulate the exported data:
    - remove unnecessary data (like like object id).
    - capitalize string where needed.
    - hide clear password.
    - sort the data by 'firstname' field.
5. show web page with the manipulated data,
you can use web server like nginx or use web framework in your code. 
