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

1. DockerHub account.
2. Docker service installed on the host.
3. Create your own public repository which will be shared with us.
#### Exercise flow:
1. Pull mongo version 4.0.4 container.
2. Create new database inside the mongo container:
    - database data is in 'data.txt' file. 
    - database name: 'cr-db'.
    - collections name 'users'.
    - you can use mongo native commands inside the container or write code. 
3. Export the database data from the container to the host:
    - write code to do that method.
4. Manipulate the exported data:
    - remove unnecessary data (like like object id).
    - capitalize string where needed.
    - hide clear password.
    - sort the data by 'firstname' field.
5. Show web page with the manipulated data,
you can use web server like nginx or any web framework as desired. 

#### Share your repo:
1. Inside your repository go to 'settings'.
2. Select 'Collaboration'.
3. Add the following users:
    - **cr-benraz**
    - **cr-dorshaul**
4. let us know when you done.

###
**Good Luck!**
