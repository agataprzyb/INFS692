# INFS692

In this repository you will find: 

RMD Files:
- INFS 692 - Final Project Model 1
- INFS 692 - Final Project Model 2
- INFS 692 - Final Project Model 3

PDF file:
- INFS-692---Final-Project-Model-1.pdf

Data: 
- radiomics_completedata.csv

Files that were unsuccessful when trying to output to PDF using Miktex:

- INFS-692---Final-Project-Model-1.txt
- INFS-692---Final-Project-Model-3.txt

- INFS-692---Final-Project-Model-1.tex
- INFS-692---Final-Project-Model-3.tex


##### PROBLEMS #####

##### Model 2 #####

Because of a Keras error with Windows, I was not able to complete this model. I only wrote the code how I thought it would be
but didn't execute it. 
This was the error I received. After trying to install tensorflow, I still had a different error that put me in a loop:


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Error: Valid installation of TensorFlow not found.

Python environments searched for 'tensorflow' package:
 C:\Users\Agatka\AppData\Local\r-miniconda\envs\r-reticulate\python.exe

Python exception encountered:
 Traceback (most recent call last):
  File "C:\Users\Agatka\AppData\Local\R\win-library\4.2\reticulate\python\rpytools\loader.py", line 119, in _find_and_load_hook
    return _run_hook(name, _hook)
  File "C:\Users\Agatka\AppData\Local\R\win-library\4.2\reticulate\python\rpytools\loader.py", line 93, in _run_hook
    module = hook()
  File "C:\Users\Agatka\AppData\Local\R\win-library\4.2\reticulate\python\rpytools\loader.py", line 117, in _hook
    return _find_and_load(name, import_)
ModuleNotFoundError: No module named 'tensorflow'


You can install TensorFlow using the install_tensorflow() function.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
The rest of the code was written using the instructions, but whether or not it executes is not verifiable for me.


##### Model 3 Errors in PDF output #####

Everything was fine when I knitted to PDF for model 1, but when I tried for model 3, I received this error:

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

! Sorry, but C:\Users\Agatka\AppData\Local\Programs\MiKTeX\miktex\bin\x64\pdflatex.exe did not succeed.

! The log file hopefully contains the information to get MiKTeX going again:

!   C:\Users\Agatka\AppData\Local\MiKTeX\miktex\log\pdflatex.log

Error: LaTeX failed to compile INFS-692---Final-Project-Model-3.2.tex. See https://yihui.org/tinytex/r/#debugging for debugging tips. See INFS-692---Final-Project-Model-3.2.log for more info.
Execution halted
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~


I updated all of Miktex (uninstalled, then back to installed), used the debugging instructions for Latex, but the error still persisted. 
I thought maybe I made a mistake and went to knit the pdf for Model 1, but that wasn't working either. THankfully the first time I did it, it worked.
Which is a shame, I could have had at least 2/3 pdfs working. 

