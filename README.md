# Login2Xplore-Works
# Project Management Form

## Description
This project is a web-based Project enrollment form that allows users to enter and store student data using JsonPowerDB. It provides functionalities to save, update, and reset project information in the database.

## Table of Contents
- [Description](#description)
- [Benefits of using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Syntax](#easiest-syntax-usage-)
- [Release History](#release-history)
- [Illustration ](#illustration)
- [Scope of Functionalities](#scope-of-functionalities)
- [Sources](#sources)

## Benefits of using JsonPowerDB
-Proprietary algorithm for High-Performance CRUD operations. Multiple times faster than popular DBMS.
-Serverless support for faster development - A UI developer can develop the dynamic application.
-DBMS with built-in web/application server and embedded caching makes the performance lightning fast.
-Server-side Native NoSQL - best query performance.
-In-built support to query on multiple JPDB databases.
-Multi-mode DBMS - Document DB, Key-Value DB, RDBMS support.
-Schema-free - easy to develop and maintain.
-Web-services API - Can be used with any programming language supporting HTTP.

## *Easiest Syntax Usage :*
    
    // GET - Query
    
    {
    "token": "90xxx665|-319493xxxxx455903|90xxxxxx",
    "cmd": "GET",
    "dbName": "COLLEGE-DB",
    "rel": "PROJECT-TABLE",
    "jsonStr":{
        "ProjectName": "Random name"
        }
    }
    
    // INSERT - Query
    
    {
      "token" : "90xxx665|-319493xxxxx455903|90xxxxxx",
      "cmd" : "PUT",
      "dbName" : "COLLEGE-DB",
      "rel" : "PROJECT-TABLE",
      "jsonStr" : {
        
            }
    }
    
*If there is no Database named - 'Employee', It will automatically create a Database with the name without forcing developers to write code or throwing hundreds of errors.*

## Release History
- [Version 1.0.0](https://github.com/your-username/your-repo/releases/tag/v1.0.0) - Initial release of the Project Management Form with JsonPowerDB integration.



## Illustrations
Include relevant screenshots or images showcasing the Project Management Form and its features.

![image](https://github.com/Rhythm-cmd/ProjectManagementForm/assets/67383671/fdb4935b-0ef9-4fc0-b868-e14590c71701)
![image](https://github.com/Rhythm-cmd/ProjectManagementForm/assets/67383671/7031de29-e2cd-4f17-88fd-06c27b243ce8)
<img width="953" alt="image" src="https://github.com/Rhythm-cmd/ProjectManagementForm/assets/67383671/a911d6cc-3e0e-43b4-ba3b-d646814b811e">
-Recently added entry.




## Scope of Functionalities
- Input validation for required fields.
- Save project data to JsonPowerDB.
- Update existing project data.
- Reset the form to its initial state.

## Sources
- [JsonPowerDB Documentation](https://login2explore.com/jpdb/docs.html)
- [Bootstrap Framework](https://getbootstrap.com/)
- [JsonPowerDB Functions](https://login2explore.com/jpdb/resources/js/0.0.4/jpdb-commons.js)
