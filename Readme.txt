#Method 1
1. Install the program without license.
2. Replace the patch folder to the program dir.
3. Open the program, select the license file and finish.

#WARNING (Method 2) (See Install_Guide.pdf)
1. You can setup the ACT_INC_LICENSE_FILE user environment, value is the license.dat.

Run installation;
Select the second option "Install DownStream Products";
Specify the license file license2021.dat from the Patch folder (it will ask 2 times);
Specify the license file license2021.dat from the Patch folder for the environment variable;
Select the options you are interested in for installation (sentinel driver can be removed);
Copy with file replacement the contents of the Patch folder to the directory with the program
 (instead of copying the corrected files, you can cure the program yourself,
  by running the patcher CSTpatcher15.cmd and specifying the directory with the program files);
Set the ACT_INC_LICENSE_FILE environment variable to the path to the copied license file;
Reboot the system to apply the changes.
