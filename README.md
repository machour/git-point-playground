## client.Namespaces

<dl>
<dt><a href="#repos">repos</a> : </dt>
<dd><p>Repositories endpoint</p>
</dd>
<dt><a href="#users">users</a> : </dt>
<dd><p>Users endpoint</p>
</dd>
<dt><a href="#orgs">orgs</a> : </dt>
<dd><p>Organizations endpoint</p>
</dd>
<dt><a href="#snippets">snippets</a> : </dt>
<dd><p>Snippets endpoint (Gists)</p>
</dd>
<dt><a href="#issues">issues</a> : </dt>
<dd><p>Issues endpoint</p>
</dd>
<dt><a href="#reactions">reactions</a> : </dt>
<dd><p>Reactions endpoint</p>
</dd>
<dt><a href="#search">search</a> : </dt>
<dd><p>Search endpoint</p>
</dd>
</dl>

<a name="repos"></a>

## client.repos : 
Repositories endpoint


* [repos](#repos) : 
    * [.fork(repoId, orgId)](#repos.fork)
    * [.get()](#repos.get)
    * [.getById(id)](#repos.getById)
    * [.getContributors(repoId)](#repos.getContributors)
    * [.getForOrg(userId)](#repos.getForOrg)
    * [.getForUser(userId)](#repos.getForUser)
    * [.getForks(repoId)](#repos.getForks)
    * [.getReadme(repoId)](#repos.getReadme)

<a name="repos.fork"></a>

### client.repos.fork(repoId, orgId)
Forks a repo


| Param | Type | Description |
| --- | --- | --- |
| repoId | <code>string</code> | The repo id |
| orgId | <code>string</code> | An optional org id where to fork the repo |

<a name="repos.get"></a>

### client.repos.get()
Gets the repos for the authenticated user

<a name="repos.getById"></a>

### client.repos.getById(id)
Gets a repo by its id


| Param | Type | Description |
| --- | --- | --- |
| id | <code>string</code> | The repo id |

<a name="repos.getContributors"></a>

### client.repos.getContributors(repoId)
Get all contributors for the given repo


| Param | Type | Description |
| --- | --- | --- |
| repoId | <code>string</code> | The repo id |

<a name="repos.getForOrg"></a>

### client.repos.getForOrg(userId)
Gets the repos of the given org


| Param | Type | Description |
| --- | --- | --- |
| userId | <code>string</code> | The user id |

<a name="repos.getForUser"></a>

### client.repos.getForUser(userId)
Gets the repos of the given user


| Param | Type | Description |
| --- | --- | --- |
| userId | <code>string</code> | The user id |

<a name="repos.getForks"></a>

### client.repos.getForks(repoId)
Gets the forks of a repo


| Param | Type | Description |
| --- | --- | --- |
| repoId | <code>string</code> | The repo id |

<a name="repos.getReadme"></a>

### client.repos.getReadme(repoId)
Gets a repo `README.md` file


| Param | Type | Description |
| --- | --- | --- |
| repoId | <code>string</code> | The repo id |

<a name="users"></a>

## client.users : 
Users endpoint


* [users](#users) : 
    * [.get()](#users.get)
    * [.getById(id)](#users.getById)
    * [.getFollowers(userId)](#users.getFollowers)
    * [.getFollowersForUser(userId)](#users.getFollowersForUser)
    * [.followUser(userId)](#users.followUser)
    * [.unfollowUser(userId)](#users.unfollowUser)

<a name="users.get"></a>

### client.users.get()
Gets the authenticated user

<a name="users.getById"></a>

### client.users.getById(id)
Gets a user by its id


| Param | Type | Description |
| --- | --- | --- |
| id | <code>string</code> | The user id |

<a name="users.getFollowers"></a>

### client.users.getFollowers(userId)
Gets the authenticated user's followers


| Param | Type | Description |
| --- | --- | --- |
| userId | <code>string</code> | The user id |

<a name="users.getFollowersForUser"></a>

### client.users.getFollowersForUser(userId)
Gets a user's followers


| Param | Type | Description |
| --- | --- | --- |
| userId | <code>string</code> | The user id |

<a name="users.followUser"></a>

### client.users.followUser(userId)
Follow a user


| Param | Type | Description |
| --- | --- | --- |
| userId | <code>string</code> | The user id |

<a name="users.unfollowUser"></a>

### client.users.unfollowUser(userId)
Unfollow a user


| Param | Type | Description |
| --- | --- | --- |
| userId | <code>string</code> | The user id |

<a name="orgs"></a>

## client.orgs : 
Organizations endpoint


* [orgs](#orgs) : 
    * [.get()](#orgs.get)
    * [.getById(orgId)](#orgs.getById)
    * [.getForUser()](#orgs.getForUser)
    * [.getMembers()](#orgs.getMembers)

<a name="orgs.get"></a>

### client.orgs.get()
Gets the orgs for the authenticated user

<a name="orgs.getById"></a>

### client.orgs.getById(orgId)
Gets an org by its id


| Param | Type | Description |
| --- | --- | --- |
| orgId | <code>string</code> | The org id |

<a name="orgs.getForUser"></a>

### client.orgs.getForUser()
<a name="orgs.getMembers"></a>

### client.orgs.getMembers()
<a name="snippets"></a>

## client.snippets : 
Snippets endpoint (Gists)


* [snippets](#snippets) : 
    * [.get()](#snippets.get)
    * [.getById(snippetId)](#snippets.getById)
    * [.getForUser(userId)](#snippets.getForUser)

<a name="snippets.get"></a>

### client.snippets.get()
Gets the snippets for the authenticated user

<a name="snippets.getById"></a>

### client.snippets.getById(snippetId)
Gets a snippet by its id


| Param | Type | Description |
| --- | --- | --- |
| snippetId | <code>string</code> | The snippet id |

<a name="snippets.getForUser"></a>

### client.snippets.getForUser(userId)
Gets the snippets of the given user


| Param | Type | Description |
| --- | --- | --- |
| userId | <code>string</code> | The user id |

<a name="issues"></a>

## client.issues : 
Issues endpoint


* [issues](#issues) : 
    * [.addAssignees()](#issues.addAssignees)
    * [.addLabels()](#issues.addLabels)
    * [.create()](#issues.create)
    * [.createComment()](#issues.createComment)
    * [.deleteComment()](#issues.deleteComment)
    * [.get(repoId, issueId)](#issues.get)
    * [.getAssignees()](#issues.getAssignees)
    * [.getForRepo()](#issues.getForRepo)
    * [.lock()](#issues.lock)
    * [.removeAssignees()](#issues.removeAssignees)
    * [.unlock()](#issues.unlock)

<a name="issues.addAssignees"></a>

### client.issues.addAssignees()
<a name="issues.addLabels"></a>

### client.issues.addLabels()
<a name="issues.create"></a>

### client.issues.create()
<a name="issues.createComment"></a>

### client.issues.createComment()
<a name="issues.deleteComment"></a>

### client.issues.deleteComment()
<a name="issues.get"></a>

### client.issues.get(repoId, issueId)
Gets an issue by its repo & number


| Param | Type | Description |
| --- | --- | --- |
| repoId | <code>string</code> | The repo id |
| issueId | <code>string</code> | The issue id |

<a name="issues.getAssignees"></a>

### client.issues.getAssignees()
<a name="issues.getForRepo"></a>

### client.issues.getForRepo()
<a name="issues.lock"></a>

### client.issues.lock()
<a name="issues.removeAssignees"></a>

### client.issues.removeAssignees()
<a name="issues.unlock"></a>

### client.issues.unlock()
<a name="reactions"></a>

## client.reactions : 
Reactions endpoint


* [reactions](#reactions) : 
    * [.createForCommitComment()](#reactions.createForCommitComment)
    * [.createForIssue()](#reactions.createForIssue)
    * [.createForIssueComment()](#reactions.createForIssueComment)
    * [.createForPullComment()](#reactions.createForPullComment)
    * [.delete()](#reactions.delete)
    * [.getForCommitComment()](#reactions.getForCommitComment)
    * [.getForIssue()](#reactions.getForIssue)
    * [.getForIssueComment()](#reactions.getForIssueComment)
    * [.getForPullComment()](#reactions.getForPullComment)

<a name="reactions.createForCommitComment"></a>

### client.reactions.createForCommitComment()
<a name="reactions.createForIssue"></a>

### client.reactions.createForIssue()
<a name="reactions.createForIssueComment"></a>

### client.reactions.createForIssueComment()
<a name="reactions.createForPullComment"></a>

### client.reactions.createForPullComment()
<a name="reactions.delete"></a>

### client.reactions.delete()
<a name="reactions.getForCommitComment"></a>

### client.reactions.getForCommitComment()
<a name="reactions.getForIssue"></a>

### client.reactions.getForIssue()
<a name="reactions.getForIssueComment"></a>

### client.reactions.getForIssueComment()
<a name="reactions.getForPullComment"></a>

### client.reactions.getForPullComment()
<a name="search"></a>

## client.search : 
Search endpoint


* [search](#search) : 
    * [.repos()](#search.repos)
    * [.users()](#search.users)

<a name="search.repos"></a>

### client.search.repos()
<a name="search.users"></a>

### client.search.users()
