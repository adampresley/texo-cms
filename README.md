# Texo CMS

This repository house the code for the Texo CMS application. Texo is Latin for *construct* or *build*. 

## Setting Up a Test Server

```bash
$ grunt build-test
$ cd bin && source ../env/bin/activate
$ fab -H user@server setupOS setupDirectory:user=user setupVirtualEnvironment uploadApp
$ fab -H user@server setupFirstUser:email=user@user.com,firstName=User,lastName=User
$ fab -H user@server uploadAndImportMarkdown:directory=/home/user/content
```
