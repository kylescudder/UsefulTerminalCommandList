# UsefulTerminalCommandList
A list of useful terminal commands, because I have a memory like a sieve

## Windows Terminal open split panel with 2 PowerShell tabs:
 ```
 wt -p "Windows PowerShell" `; split-pane -V "Windows PowerShell"
 ```
 
## Windows Terminal add Title to Windows Terminal:
 Add the `--title "YOUR TITLE"` tag
 
## Install npm package just for that repo and project
### The `-i` is short for `install`

 ```
 npm -i PACKAGE-NAME
 ```
 
## Install npm package just for entire machine
### The `-g` is short for `global`
 
 ```
 npm -i -g PACKAGE-NAME
 ```
 
## Install npm package just developement (things like webpack and ESLint)
### The `-D` is short for `--save-dev` which just installs in the devDependencies
 
 ```
 npm -i -D PACKAGE-NAME
 ```
 
## Uninstall npm package
### All previous tags apply to uninstall too.
 ```
 npm uninstall
 ```
 
 ## If you are setting up a package.json you can always add `watch` to your script, like so:
 
`"watch": "concurrently \"rollup -c -w\" \"webpack `**`--watch`**`--mode production --devtool hidden-source-map\""`

## Create a new dotnet project
```
dotnet new [PROJECT TYPE]
```

## Add -o to specificy the output folder:

```
-o
```

## Self explanatory
```
 --no-https
```

## dotnet project commands

 ```
 dotnet run
 dotnet build
 dotnet publish
 ```
 
## Adds NUGET package

 ```
 dotnet add package PACKAGE-NAME
 ```

 
 
 
