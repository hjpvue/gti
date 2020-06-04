# General Tool Interface

A command-line tool with magical abilities and interesting errors. Inspired by the Infernal family of computing languages. We aim to automate routine tasks to the extent that we deal only with pure development.

## Installation

### Node Package Manager
```
npm -i -g --only-save -dev gti
```

## Usage

```
gti command
//output
```

# CLI commands:

gti -notry [dir/file/path] --implements standard file checking before executing/compiling the passed file(s).
gti -gobuy [number]  --sends an email to a random Go Developer and asks to purchase Go for the user specified amount in dollars.
gti -minify [dir/file] --if a directory/file is passed, minifies all the files in the directory via direct overwrite and appends the file names.
gti -portal [PROJECT DIRECTORY] [TARGET PLATFORM]  --this will iterate passed empty directories and auto-match to a .gradle .gulp .android .xcode .geany .ruby .crystallang .erlang .json type project and then setup the relevant evironment and then attempt to build and/or run the identified project. If run fails, it will append the source code and repeat forever.
gti -teleport [Destination URI/URL/dir]  --makes a copy of the current working directory contents and moves everything to target directory or network address(as a HTTP POST) whereafter the original files will be deleted if unused for 90 seconds (ignored if failed due to subsequent operations)
gti -duplicate [directory/file]  --makes a copy of the input in the current working directory
gti [package-name] [COMMAND]  --passes given command to named package/OS-command. If package is not installed, searches for it, downloads it, installs and runs the original passed command again. If sudo, cd, mkdir, chmod etc. commands are required they are relayed interactively. If package not found, provides selectable list of suggested repo's to add automatically and then repeats the initial attempt.
gti -mirror [opt:maxlenght, filetype, path]  --prints all previously entered CLI commands across all sessions to screen or saves to file including file edits.
gti -simplify [path/to/config.json] [package name/URL endpoint]  --runs an automated test suite against selected API surface and aliases similar native API commands, lists them, outputs to terminal screen and prompts to save.
gti -immortalise [dir/file/url] [contact@mail.net]  --either returns archived link or attempts to run a host web server and get a snapshot, will also look for 'snapshot.png' inside directory and confirm with prompt. contact email address MUST be passed. Does not validdate.
gti -send [file/dir/path | defaults to entire gzipped pwd if none] [DESTINATION]  --takes any destination, if email address then injects into mail_template.html if file or as zipped attachment if a directory. If a package name is passed, will try all routes to implement package network export mechanism. 
gti -invoke [COMMAND/path to bin/bash]  --will quit at first success, has timeout auto. Default user when used with cURL, chron, ftp, http RECIEVE/UPDATE/PUT/POST/GET requests. If command not found, will run analysis and search untill success. Platform independant.
gti -fortify [dir/url/file]  --defaults to current machine, sets up dynamic interactive firewall with pen-testing and retaliation capabilities. If a directory is passed, it encrypts it recursively and prompts for further input. If a url is passed, it interactively generates a profile of the network resource, and prompts for further input. If a file is passed, it is encrypted after being minified and obfuscated.
gti -analyse
gti -instantiate [projectname] [/specify/path/to/dest (defaults to new folder in pwd)] [target platform, version (if none @latest)]   --scaffolds a new project file structure with given name and for given platform at provided destination.
gti -publish  [service provider name, access credentials/path/to/file.pem]  --defaults to current working directory if none specified, uses preset parameters inside publish.json 
