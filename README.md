# GitHub using API writtten in Shell Scripting

## In this Project we will be retrieving information from GitHub account using Shell Scripting
                 
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


5. Now execute the file by passing the parameters for GitHub Token and Rest Expression 

```
./cmds.sh <GitHub-Token> <Rest-Expression>
```

---
## In this Project we will be listing the users that have permission to a repository in a GitHub Organization using Shell Scripting 

You can communicate with an application using below

- CLI
- API

We have a shell Script written retrieve information about users from GitHub using GitHub Token, Username and REST API expression

![image](https://github.com/Pavan-1997/GitHub_Organization_API_Shell/assets/32020205/79d113c0-64e8-4fed-ab9d-4c28b8c0d144)

All the commands are written in shell and executed in Ubuntu Server 

1. Clone the repository

```
git clone https://github.com/Pavan-1997/GitHub_Organization_API_Shell.git
```


2. Pass the enviroment variables for GitHub Username and GitHub Token which is later accessed by the script during execution

```
export username="User-Name"
export token="Token"
```


3. Install JQ to extract the data from JSON

```
sudo apy install jq -y
```


4. Give full permission to the cmds.sh file

```
chmod 777 cmds_orgaization.sh
```


5. Now execute the file by passing the parameters for Organization Name and Repository Name

```
./cmds.sh <Organization-Name> <Repository-Name>
```

![image](https://github.com/Pavan-1997/GitHub_Organization_API_Shell/assets/32020205/caf023dd-a1b8-422e-bb38-e0a83cec4c0f)


6. Made use of a Helper function which can prompt with values as below if any of the parameters is not passed during the script execution

![image](https://github.com/Pavan-1997/GitHub_Organization_API_Shell/assets/32020205/0e1d80b1-5da0-43af-8553-f9298a70c1cd)



