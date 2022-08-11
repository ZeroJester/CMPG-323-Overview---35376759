# CMPG-323-Overview---35376759
This is a public GitHub repository for CMPG 323 - Project 1


## Repositories:
    Repository 1:   This repository will be used for Project 1 (Current Link)
    Repository 2:   This repository will be used for Project 2 (link here)
    Repository 3:   This repository will be used for Project 3 (link here)
    Repository 4:   This repository will be used for Project 4 (link here)
    Repository 5:   This repository will be used for Project 5 (link here)

    Each project will be done in a seperate, dedicated repository.
    The links to each repository will be added as they are created later on.
   
## Diagram

![Project1-Planning-Diagram](https://user-images.githubusercontent.com/85791779/184122883-5b47c1d8-62fb-4f21-b49d-1d34e97ef25b.png)


## Branching Strategy
    I will be using the GitHub Flow branching strategy. 
    This strategy allows me to focus on one feature or hot-fix at a time, improving efficiency.
    This is a very simple, yet effective branching strategy, and can even be used with complex projects.
    I will be the only person working on these projects, so only one version of the code will be available at all times.
    
    Branches I will be using:
        -main
        -feature
        
    Features will first be released into the feature branch for testing and evaluation.
    After the feature is approved, it will be merged into the main branch.
    Rollbacks to the main branch can be performed if necessary.
        
        

## Implimentation of a .gitignore file
    The .gitignore file of each repository will be used to hide information that will be useless to the user, or might be sensitive information of the creator of the project. This information might include notes taken, a to-do list, a list of features that need to be added, a list of hot-fixes that need to be done and implemented, or sensitive information such as usernames, passwords or any other credentials that might not be of use to the users.


## Security and Privacy of Sensitive Information
    For sensitive information, a seperate textfile will be created. The program will read data from this textfile when necessary, but the textfile will not be available to the users of the program. This method can be implemented through various GitHub security features such as "libsodium sealed box". This will ensure the safety of sensitive credentials, and users, other than the creator, will not be able to see, edit or use this information.
