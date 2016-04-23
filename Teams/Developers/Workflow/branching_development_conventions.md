[ common ] branch, environment,hostname conventions

## basecamp project name == project id. 
if we have "api" development project in basecamp, it is project id.

## we use auto-linking
for documentation, we use a lot of automations and linking, so this project ids, branches, etc should be kept automatically. 

### No shortening/omit.
e.g. no "front", but "frontend" if it using this string as project name 

## repository and branching conventions 
basecamp project.name == project id == repository.name

## the host names is reversed format of branch and repository name.
e.g. api repository's development  branch contents are automatically mapped and deployed to http://development.api.sl.ht using CI. you can expected those all of staging.sensorLogSteaming to staging.shop or those. 

## environment string == branches. 
development,staging,production. they are the ids to show the environment. and they are also, the branches.

## usually, frontend, client, and backend should point the right thing and connected

so the iOS constants of the web view baseurl, of development branch,  should point at http://development.sl.ht. and the api baseurl should be http://development.a.sl.ht, if this needs shop or auth, then development.auth.a.sl.ht

another example, the staging branch code of gateway_firmware should use the baseurl as http://staging.a.sl.ht ( and port maybe not 80 ) 


