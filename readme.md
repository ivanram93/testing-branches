Crear nueva ramificacion:
```
$ git checkout -b beta
```

Hacer commits normal y cuando se haga el push ya sea a la branch por defecto o a la nueva usar:
```
$ git push -u origin BRANCH-NAME
```

http://git-scm.com/book/en/Git-Branching-Basic-Branching-and-Merging
In your case you would do the following:
```
$ git checkout a # you will switch to branch a
$ git merge b # this will merge all changes from branch b into branch a
$ git commit -a # this will commit your changes
```
take a look at above link to get the full picture.
