# GitHub using API writtten in Shell Scripting

## In this Project we will be listing the users that have permission to a repository in a GitHub account using Shell Scripting

We have a shell Script written retrieve information about users from GitHub using GitHub Token, Username and REST API expression
                 
All the commands are written in shell and executed in Ubuntu Server  
  


  
1. Clone the repository

```
git clone https://github.com/Pavan-1997/GitHub_API_Shell.git
```


2. Install JQ to extract the data from JSON

```
sudo apy install jq -y
```


4. Give full permission to the cmds.sh file

```
chmod 777 cmds.sh
```


5. Now execute the file by passing the parameters for GitHub Username and Repository Name

```
./cmds.sh <User-Name> <Repository-Name>
```

 
