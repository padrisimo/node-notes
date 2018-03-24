# node-notes CLI App
Node notes is a Command Line Interface Application wich means that it works in a terminal like the old school programs without GUI.

### To add a Note
```
> node app.js add --title="toDo" --body="kill humans"
```
or
```
> node app.js add -t="toDo later" -b="read comic books"
```
Yo can use the full arguments (--title) or their flag version (-t), both works the same in any command.

### List all Notes
```
> node app list
```

### Read one Note (search by title)
``` 
> node app.js read --title="toDo"
```

### Remove one Note (search by title)
``` 
> node app.js remove --title="toDo"
```

### Show Available Commands and Use (help)
``` 
> node app.js --help
```

### Show help and descriptions of one Command
You may replace **add** with any other command (list, remove, read)
``` 
> node app.js  add --help
```
