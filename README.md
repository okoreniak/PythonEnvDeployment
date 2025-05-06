# PythonEnvDeployment
Python environment deployment
- Windows
  Install python3 using Microsoft strore
  install pipx with command
  "python3 -m pip install --user pipx"
  It is possible (even most likely) the above finishes with a WARNING looking similar to this:

WARNING: The script pipx.exe is installed in `<USER folder>\AppData\Roaming\Python\Python3x\Scripts` which is not on PATH

If so, go to the mentioned folder, allowing you to run the pipx executable directly. 
Enter the following line (even if you did not get the warning):

".\pipx.exe ensurepath"

Verify pipx is installed and works.

Install connan with pipx (see https://docs.conan.io/2/installation.html for details)

 "pipx install conan"

 
