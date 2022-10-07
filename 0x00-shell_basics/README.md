pwd - Prints the absolute path name of the current working directory
ls - Display the contents list of your current directory
cd ~ - Changes the working directory to the user’s home directory and you are not allowed to use any shell variables
ls -l - Displays current directory contents in a long format
ls -la - Display current directory contents, including hidden files (starting with .). Use the long format
ls -na - Display current directory contents in a long format, with user and group IDs displayed numerically and hidden files (starting with .)
mkdir /tmp/my_first_directory - Creates a directory named my_first_directory in the /tmp/ directory
mv /tmp/betty /tmp/my_first_directory - Move the file betty from /tmp/ to /tmp/my_first_directory
rm /tmp/my_first_directory/betty - Delete the file betty
rm -r /tmp/my_first_directory/ - Delete the directory my_first_directory that is in the /tmp directory
cd - - Changes the working directory to the previous one
ls -la . .. /boot - lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format
file /tmp/iamafile - prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script
ln -s /bin/ls __ls__ - Creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory
cp -un *.html ../ - Creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. You can consider that all HTML files have the extension .html
mv [[:upper:]]* /tmp/u - Creates a script that moves all files beginning with an uppercase letter to the directory /tmp/u. You can assume that the directory /tmp/u will exist when we will run your script
rm *~ - Creates a script that deletes all files in the current working directory that end with the character ~
mkdir -p welcome/to/school/ - Creates a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory. You are only allowed to use two spaces (and lines) in your script, not more
ls -amp | sort -d - Lists all the files and directories of the current directory, separated by commas (,), directory names should end with a slash (/), files and directories starting with a dot (.) should be listed, the listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning, only digits and letters are used to sort; Digits should come first, you can assume that all the files we will test with will have at least one letter or one digit and the listing should end with a new line
0 string SCHOOL School data !:mime School - Creates a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0
