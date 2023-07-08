# ninja-rhel

Ninja package is not available in the default repositories of RHEL 8.7.

You can try an alternative method to install Ninja on your system by using the Python package manager, pip. Here's how you can do it:

Make sure you have the python3-pip package installed. If not, you can install it using the following command:
```
sudo dnf install python3-pip
```
Once python3-pip is installed, you can use pip to install Ninja by running the following command:
```
pip3 install ninja
```
This command will install Ninja and its dependencies using pip.

Verify the installation by checking the Ninja version:
```
ninja --version
```
This should display the installed Ninja version if the installation was successful.
