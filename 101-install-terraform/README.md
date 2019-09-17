# Install Terraform

Use `tfenv` to help the installation and maintaining multiple versions of Terraform in our local machines. Here are the steps to install and use `tfenv`.
- Make sure curl installed, if not install with `sudo apt-get install curl`
- Install tfenv https://github.com/tfutils/tfenv 
- Create a ~/.tfenv/version file containing a default terraform version, e.g. "0.11.10".
- Install terraform, e.g. version 0.11.10
```
tfenv install 0.11.10
```
- List terraform version that you’ve installed
```
tfenv list
```
- You can install different versions, and change your default terraform version using `tfenv use`
```
tfenv install 0.11.12
tfenv use 0.11.12
```
