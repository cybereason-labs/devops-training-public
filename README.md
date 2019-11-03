# Welcome to Cybereason DevOps training

                         8o&&ooo*                                      .ooo&o&8*                         
                          o#ooo&&&&&&&&o&&o&&&&&oo:::::oo&&&&o&ooo&&&&&&&&&o8#                          
                            ##&o&&&&&&o&ooo&o&&ooo&&&&oooo&&o&&ooo&&&&&&o&##.                            
                             8##&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&##8                             
                              o&oo*o&&o&&&&&&&&&&&&&&&&&&&&&&&&&&oo&o&o&o&                              
                             oo&    oo&&&&&&&&&&&&&&&&&&&&&&&&&&&&oo    &oo*                             
                            o&&   8@  oo&o&&&&&&&&&&&&&&&&&&&&&o&o  8@   o&&*                            
                           &oo   @@@@:  oo&oo&&&&&&&&&&&&&&&o&o&:  @@@@   &oo                           
                           &&&  8@@@@@   *o&o&&&&&&&&&&&&&&&&&&   .@@@@@  *oo                           
                           &o&  8@@@@   @  o&&&&&&&&&&&&&&&o&  8o  #@@@@  *oo                           
                           :&&   @@@o@@@@@  o&o&&&&&&&&&o&o&  @@@@@8@@@   ooo                           
                            ooo   #@@@@@@@@& *oo&&&&&&&&&&o  @@@@@@@@@   &o&                            
                             ooo*    o@@@@@@#  &oo&&&&&&&: #@@@@@@@     o&o                             
                               oo&&             &oo&&&&o*            ooo&                               
                                  &o&&&ooooo&*   oo&&&&   .ooooooo&o&&.                                  
                                       oooo&&&&&o&&&&&oo&o&&&oo&o.                                       
                                                 o&&ooo                                                 
                                                   oo                                                   
                                                    :                                                    

#### Exercise requirements:

1. docker account.
2. docker service installed on the host.
3. create your own public repository which will be shared with us.
#### Exercise flow:
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

#### Share your repo:
1. inside your repository go to 'settings'.
2. select 'Collaboration'.
3. add the following users:
    - **cr-benraz**
    - **cr-dorshaul**
4. let us know when you done.

###
**Good Luck!**