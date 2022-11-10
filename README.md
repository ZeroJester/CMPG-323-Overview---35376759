# CMPG-323-Overview---35376759
This is a public GitHub repository for CMPG 323 - Project 1


## Repositories:
    Repository 1:   This repository will be used for Project 1 (CMPG-323-Overview---35376759)
    Repository 2:   This repository will be used for Project 2 (https://github.com/ZeroJester/CMPG-323-Project-2---35376759)
    Repository 3:   This repository will be used for Project 3 (https://github.com/ZeroJester/CMPG-323-Project-3---35376759)
    Repository 4:   This repository will be used for Project 4 (https://github.com/ZeroJester/CMPG-323-Project-4---35376759)
    Repository 5:   This repository will be used for Project 5 (https://github.com/ZeroJester/CMPG-323-Project-5---35376759)

    Each project will be done in seperate, dedicated repositories.
   
## Diagram

![diagram](https://user-images.githubusercontent.com/85791779/199679056-39e38340-383a-4d58-a96a-480b8270d8b0.png)





## Branching Strategy
    GitHub Flow

    I will be using the GitHub Flow branching strategy for each project, as the projects are seperate. 
    This strategy allows me to focus on one feature or hot-fix at a time, improving efficiency.
    This is a very simple, yet effective branching strategy, and can even be used with complex projects.
    I will be the only person working on these projects, so only one version of the code will be available at all times.
    
    Branches I will be using:
        -main
        -feature
        -hotfix
        
    Features will first be released into the feature branch for testing and evaluation.
    After the feature is approved, it will be merged into the main branch.
    Rollbacks to the main branch can be performed if necessary.
        
        

## Implimentation of a .gitignore file
    The .gitignore file of each repository will be used to hide information that will be useless to the user, 
    or might be sensitive information of the creator of the project. This information might include notes taken, 
    a to-do list, a list of features that need to be added, a list of hot-fixes that need to be done and implemented, 
    or sensitive information such as usernames, passwords or any other credentials that might not be of use to the users.
    

## Security and Privacy of Sensitive Information
    For sensitive information, a seperate file (typically a textfile) will be created. The program will read data from 
    this file when necessary, but the file will not be available to the external users of the program. This method can 
    be implemented through various GitHub security features such as "libsodium sealed box". By using this method, the 
    sensitive information will be encrypted, and can only be decrypted by a user that has a valid access key. 
    This will ensure the safety of sensitive  information, and users, other than the creator, will not be able to see, 
    edit or use this information.
