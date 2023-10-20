# Linux
Command Line Variables

Examine the Current $PATH Variable
Determine the current working directory.
pwd
List the contents of the current directory.
ls
List the contents of the scripts folder.
ls scripts/
Run the test.sh script, specifying the path to it.
./scripts/test.sh
Attempt to run the test.sh script without specifying the path to it.
test.sh
List the current environment variables, and locate the $PATH variable.
env
Examine the $PATH variable.
echo $PATH
Append the Path to the scripts Directory to the $PATH Variable
Run the following command:
PATH="$PATH:$HOME/scripts"
Run the test.sh script again without specifying the path.
test.sh
Make the New Path Persist
View the contents of the .profile file.
cat .profile
View the $PATH variable.
echo $PATH
Source the .profile file.
source .profile
Modify the ~/.profile file to make our change permanent.
echo 'PATH="$PATH:$HOME/scripts"' >> ~/.profile
Source the .profile file again.
. .profile
View the $PATH variable again.
echo $PATH
Run the test.sh script without specifying the path again.
test.sh

Conclusion

