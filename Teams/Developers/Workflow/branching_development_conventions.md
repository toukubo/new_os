[ common ] branch, environment,hostname conventions

## basecamp7s project name is project id. 
the name of the project, in basecamp, for the development related project, is the id string. we should keep using this as id string. sl.ht

## do not shorten and omit for the id and those string in this document. 
e.g. no dev no stg but development, staging, production. no front but frontend 

## repository and branching conventions 
basecamp project.name == project id == repository.name

## the host names is reversed format of branch and repository name.
e.g. api repository's development  branch contents are automatically mapped and deployed to http://development.api.sl.ht using CI. you can expected those all of staging.sensorLogSteaming to staging.shop or those. 

## environment string == branches. 
development,staging,production. they are the ids to show the environment. and they are also, the branches.

## usually, frontend, client, and backend should point the right thing and connected

so the iOS constants of the web view baseurl, of development branch,  should point at http://development.sl.ht. and the api baseurl should be http://development.a.sl.ht, if this needs shop or auth, then development.auth.a.sl.ht

another example, the staging branch code of gateway_firmware should use the baseurl as http://staging.a.sl.ht ( and port maybe not 80 ) 


