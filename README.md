Hi, this is my analytics while learn Scripts and Shell.

About: 
    1 - multiple comands: 
        cd/; ls -l - to write without need press enter. Use '/;' for separator the comands.

Step By Step:
    1 - Create a file, example `myscript.sh`.

    2 - To specify what shell it will be used in first line of the file.
        example `#!/bin/bash`.

    3 - The symbol # represent line of coments, except on the first line of the  
        file, where the combination indicates the shell that will run the script.
    
    4 - Then is required give permission of execution to script.
        Run: `chmod a+x myscript.sh

Rdirect command output to variables.
Using backticks (``) allow you to assingn the output of a shell
command to a variable. The entire command must be between backticks.
    Example: `day=`date``

Operators:
    Equal to equal: `-q`
    Different of[not equal]: `-ne`
    Less than: `-lt`
    Less or equal: `-le`
    Greater than:`-gt`
    Greater or equal: `-ge`

Comparisons with text:
   Equal to:`=`
   Different of: `!=`
   String not empty: -n
   String is empty: -z
   
   Example: 
	'when [[ -z "response" ]]; do'
	'   echo "write a number"    '
	'   read response            '
	'done                        '

	'if [[ $value -eq 0 ]]; then '
	'   echo "Even number "      '
	' else                       '
      	'   echo "Odd number"        '
        'fi                          '

 	
