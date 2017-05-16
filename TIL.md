# Starting a Today I learnt 

To keep track of different emacs hacks I read about and want to get into my workflow.

## Global hacks:
    C-x +  balance windows 

## Compilation window i.e. compile mode: 
    g - recompiles (runs the same make command as before)
    tab OR M-n - goes to the next error
    ret - goes to the error in source


## Projectile mode:
    C-c p c - compile project from root - enter the make command in buffer
    C-c p s g - grep from root directory of the project
    C-c p b - switch to buffer of a file in current project
    C-c p k - kills all buffers of that project
 
## Python major mode:
start and keep running a python process if you want to have an ipython/jupyter workflow, where you can reevaluate different chunks of the program

    C-c C-z - go to the shell running a python process
    C-c C-l - send a file to shell 
    C-c C-r - python shell send selected region (no region = current line)

## Elpy:
    C-c C-d - finds documentation for object (either read the doc string) or do elpy-goto-definition
    M-. - go to the definition in source
    C-x 4 M-. - go to definition in another window
    C-c C-e - for code at point select it everywhere in the buffer and edit it
    C-c C-c send the buffer to python shell (similar to python major mode)

## Ibuffer mode - interactive mode

    'o' - View the buffer in another window.
    'C-o' - View the buffer in another windon, DON'T select the new window.

## Proced

A built-in major mode to examine running processes and send signals to them.

  * 's S' - interactive sort
  * 's c' - sort by CPU utilisation  
  * 'T' for tree mode. Not as pretty as pstree, but does the job
  * 'h' for help
