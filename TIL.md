# Starting a Today I learnt 

To keep track of different emacs hacks I read about and want to get into my workflow.

## Global hacks:
    C-x +  balance windows 

## Compilation window i.e. compile mode: 
    g - recompiles (runs the same make command as before)
    tab OR M-n - goes to the next error
    ret - goes to the error in source


## Projectile mode (globally active for me):
    C-c p c - compile project from root - enter the make command in buffer
    C-c p b - switch to buffer of a file in current project
    C-c p k - kills all buffers of that project
 
## Python major mode:
start and keep running a python process if you want to have an ipython/jupyter workflow, where you can reevaluate different chunks of the program

    C-c C-z - go to the shell running a python process
    C-c C-l - send a file to shell 
    C-c C-r - python shell send selected region (no region = current line)
