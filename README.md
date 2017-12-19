# Guidelines for working on the OCB MINOS DHIS2 metadata

## 1. Installation of a local DHIS2 instance
### a. Installation of Docker
#### On Windows
#### On Mac
#### On Linux

### b. Installation of the development branch of OCB DHIS2
#### Create folder
#### Git clone of the docker compose file
#### Creation of the images
#### Launch of the service

### c. Installation of the development branch of the metadata
#### Create folder
#### Git clone
#### Push metadata to the local DHIS2 instance
curl command should be enough

## 2. How to work on the local metadata
### a. Create a branch on the local metadata repository
### b. Modify the metadata from the local DHIS2 UI
### c. Pull the Metadata from DHIS2 to the local metadata repository
curl or wget command should be enough
### d. Git commit

## 3. Merge the local changes into the development branch of the central metadata repository
### a. Create a pull request
### b. Merge the pull request from the local branch to the dev branch
### c. Triggers automatically the new metadata file to the development instance of DHIS2

## 4. Promote the development environment to staging
TODO define steps

## 5. Promote the staging environment to preproduction
TODO define steps

## 6. Promote the preproduction environment to production
TODO define steps

## X. Bug fixing on the production instance
TODO to be better defined
### a. Duplicate the production environment into a new docker environment
### b. (same for local environment)
### c. Create a HOTFIX branch of the metadata repository from the master branch
### d. Commit changes 