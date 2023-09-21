> Jump to the list of [approved commands](#approved) down below

## Command Name

- Command name is usually one word, all lowercase. If multiple words can\'t be avoided, they are separated by hyphens.
- It is recommended to use a verb. Nouns and abbreviations can be
used especially if they are of common use (Kubectl, UNIX,
ect.). 
- If the command is an abbreviation, an alias will be added to be explicit 
- Avoid reuse package name as command name (i.e. config)
- Do not reuse commands for different semantic purposes
- Newly introduced commands should come from the agreed-upon list of commands or added to it


## Command Alias

- Aliases are optional, recommended if the command name is long or is an abbreviation
- They are usually shorter than the command names and help users to type command faster, abbreviations are accepted.
- Aliases are not documented but listed in the command help.
- *Use for backward compatibility*: legacy command that is not part of the agreed-upon list of commands must use the agreed-upon command as an alias
- all aliases must be unit tested


## Command Description

- A command description starts with an uppercase and doesn\'t have a full stop.
- Command descriptions will be listed on the package help, as a result the description should be one small sentence (\~70 chars)
- the parameters and options of the command are not displayed in the short description but will be in the help of the command 
- new line character is forbidden
- avoid \"(s)\" to mark plural, just use the plural form; it is easier to read for humans and screen readers.


## Optional Resource-type or Argument

Generic commands such as `new` might require an argument representing the type of the resource the command is targetting. The argument name is usually command and domain specific. Example: **new environment**, **new helm**, **new plugin** ect.

- It is usually a noun
- If multiple words can\'t be avoided, they are separated by hyphens.
- If it represents a type of resource, both singular and plural forms are recommended (use of aliases) and abbreviations are recommended as well. Example: the type **environment** should accept the following aliases **environments**, **env** and **envs**.


<a name="approved" id="approved"></a>
## Approved Commands


### Commands that initialize
When needed, this command must be run first. It will set up the environment such as initializing a new project.

`init` Initialize a new *project*


### Commands that authenticate
These commands are used to login or logout from an account.

`login` Login to *account-type* account

`logout` Logout from *account-type* account


### Commands that get
The preferred command is "get".

`get`  List one or more resources

`list` List one or more resources. Note that *list* is an acceptable synonym of *get*. If *list* is used, *get* must be the alias.

`download` Download *something* from *somewhere*. Note that *download* can be used when a resource is downloaded from a remote repository

Filtering consideration: TBD


### Commands that create
The preferred  command is *new*.

`new`  Create one or more resources from a file or stdin

`create` Create one or more resources from a file or stdin. Note that *create* is an acceptable synonym. If used, *new* must be an alias.


### Commands that edit
`edit`  Edit and update the definition of resources by using the default editor
 

### Commands that delete
The preferred command is "delete".

`delete` Delete resources

`remove` is acceptable when the resource is not destroyed i.e. removing a resource from a list.

### Commands that install
`install`  Install {object-type}

`uninstall`  Uninstall {object-type}

### Commands that update
`update` Update resources


### Commands that publish
`publish`  Publish and run an *object-type* on *environment-name* 

`unpublish`  Stop and unpublish an *object-type* from *environment-name* 
	

### Commands that run
`run` Build and run an *object-type*


### Commands that show usage
`usage`  Display the xxx and yyy of the server system resources


### Commands that show logs
`log`  Print logs of an *object-type*  


### Other commands
`build`   Build an app

`config`  Reserved word. Used by the amplify CLI.





