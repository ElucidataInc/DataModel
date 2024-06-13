# Data Model Contribution Manual

### 1. For Developers

1.1. Clone the github repo on your local machine.  
1.2. Depending on the kind of update, fork a branch using the `main` branch using  
  
  `git checkout -b <branch name>`  

    Branch naming conventions  

    Adding a new entity  
    - Use prefix add/<add_entity_x>  

    Update an existing entity (ADD, UPDATE, DELETE attribute)
    - Use prefix update/<entity_name>  
    
    Deleting an existing entity
    - Use prefix delete/<entity_name>

    Other changes pertaining to updating or creating additional documentation, updating logs/readme should follow similar conventions.

1.3. Raise a pull-request in order to merge changes with the `main` branch.    

    Pull Request tips

    - Developer can create a single PR for pushing similar type of changes. Example, updating multiple entities
    - If a developer is creating and updating entities, they need to do so using seperate pull requests
    - ALWAYS REMEMBER to do a git pull before forking any new branches from the main branch. 
    This is done to avoid useless merge conflicts later.
    - If you come across conflicts, try to resolve them with the help of a peer or the repo admin.

1.4. For each PR atleast 2 reviewers needs to be assigned.   
1.5. PRs will be merged only by the Admin of the repo after the PR is approved.  
1.6. Each change MUST be documented in the `changelog.md` file and must be included in the PR.  

    Changelog format

    <Type of change>: <Date of change in DD-MM-YYY format>
    - Change 1
    - Change 2
    
    Type of changes
    - Fixed
    - Added
    - Changed

    NOTE: Each type must be grouped together, for example:

    Unreleased: 05-03-2024

    Fixed:
    - A thing was fixed

    Added:
    - A thing was added

    Changed:
    - A thing was changed

### 2. For non-developers only

We currently do not have a mechanism for contributions from non-team members/non-developers. However, if you are willing to contribute towards the development of this project, drop an email with your requirements to pawan.verma@elucidata.io or krutika.gaonkar@elucidata.io