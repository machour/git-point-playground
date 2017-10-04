# rest-client *1.0.0*



### src/rest-client.js


#### new RestClient() 

Base REST client






##### Returns


- `Void`



#### RestClient.constructor(type, root) 

Constructor




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| type | `string`  | The API type | &nbsp; |
| root | `string`  | The API root | &nbsp; |




##### Returns


- `Void`



#### log(args) 

Logging utility for devs




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| args |  | The data to be logged | &nbsp; |




##### Returns


- `Void`



#### fork(repoId, orgId) 

Forks a repo




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| repoId | `string`  | The repo id | &nbsp; |
| orgId | `string`  | An optional org id where to fork the repo | &nbsp; |




##### Returns


- `Void`



#### get() 

Gets the repos for the authenticated user






##### Returns


- `Void`



#### getById(id) 

Gets a repo by its id




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| id | `string`  | The repo id | &nbsp; |




##### Returns


- `Void`



#### getContributors(repoId) 

Get all contributors for the given repo




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| repoId | `string`  | The repo id | &nbsp; |




##### Returns


- `Void`



#### getForOrg(userId) 

Gets the repos of the given org




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| userId | `string`  | The user id | &nbsp; |




##### Returns


- `Void`



#### getForUser(userId) 

Gets the repos of the given user




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| userId | `string`  | The user id | &nbsp; |




##### Returns


- `Void`



#### getForks(repoId) 

Gets the forks of a repo




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| repoId | `string`  | The repo id | &nbsp; |




##### Returns


- `Void`



#### getReadme(repoId) 

Gets a repo `README.md` file




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| repoId | `string`  | The repo id | &nbsp; |




##### Returns


- `Void`



#### get() 

Gets the authenticated user






##### Returns


- `Void`



#### getById(id) 

Gets a user by its id




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| id | `string`  | The user id | &nbsp; |




##### Returns


- `Void`



#### getFollowers(userId) 

Gets the authenticated user's followers




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| userId | `string`  | The user id | &nbsp; |




##### Returns


- `Void`



#### getFollowersForUser(userId) 

Gets a user's followers




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| userId | `string`  | The user id | &nbsp; |




##### Returns


- `Void`



#### followUser(userId) 

Follow a user




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| userId | `string`  | The user id | &nbsp; |




##### Returns


- `Void`



#### unfollowUser(userId) 

Unfollow a user




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| userId | `string`  | The user id | &nbsp; |




##### Returns


- `Void`



#### get() 

Gets the orgs for the authenticated user






##### Returns


- `Void`



#### getById(orgId) 

Gets an org by its id




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| orgId | `string`  | The org id | &nbsp; |




##### Returns


- `Void`



#### getForUser() 








##### Returns


- `Void`



#### getMembers() 








##### Returns


- `Void`



#### get() 

Gets the snippets for the authenticated user






##### Returns


- `Void`



#### getById(snippetId) 

Gets a snippet by its id




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| snippetId | `string`  | The snippet id | &nbsp; |




##### Returns


- `Void`



#### getForUser(userId) 

Gets the snippets of the given user




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| userId | `string`  | The user id | &nbsp; |




##### Returns


- `Void`



#### addAssignees() 








##### Returns


- `Void`



#### addLabels() 








##### Returns


- `Void`



#### create() 








##### Returns


- `Void`



#### createComment() 








##### Returns


- `Void`



#### deleteComment() 








##### Returns


- `Void`



#### get(repoId, issueId) 

Gets an issue by its repo & number




##### Parameters

| Name | Type | Description |  |
| ---- | ---- | ----------- | -------- |
| repoId | `string`  | The repo id | &nbsp; |
| issueId | `string`  | The issue id | &nbsp; |




##### Returns


- `Void`



#### getAssignees() 








##### Returns


- `Void`



#### getForRepo() 








##### Returns


- `Void`



#### lock() 








##### Returns


- `Void`



#### removeAssignees() 








##### Returns


- `Void`



#### unlock() 








##### Returns


- `Void`



#### createForCommitComment() 








##### Returns


- `Void`



#### createForIssue() 








##### Returns


- `Void`



#### createForIssueComment() 








##### Returns


- `Void`



#### createForPullComment() 








##### Returns


- `Void`



#### delete() 








##### Returns


- `Void`



#### getForCommitComment() 








##### Returns


- `Void`



#### getForIssue() 








##### Returns


- `Void`



#### getForIssueComment() 








##### Returns


- `Void`



#### getForPullComment() 








##### Returns


- `Void`



#### repos() 








##### Returns


- `Void`



#### users() 








##### Returns


- `Void`




*Documentation generated with [doxdox](https://github.com/neogeek/doxdox).*
