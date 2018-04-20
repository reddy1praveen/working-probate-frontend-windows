# Probate nodejs app
This branch  is created to do test in windows.



#for production
Follow the below steps.
There are two differnt frontend zip.
one moj-probate-frontend which was working in Pass azure.
anothe one probate-frontend which is giving troble.
Instruction to test iss same
The tar files already contains NODE_MODULES so `don't run` commands `yarn install` and `yarn setup`

in Azure pass we dont start app using start command.

We simple need to set the path.

Unix commands
=============
Go to probate fronend dir and set path node path.



``` export NODE_PATH=.  
```

and to start app

```    node server.js
```

Windows commands
================


``` set NODE_PATH .  
```

and to start app

```    node server.js
```

## Guides

## Other documentation

## Community


