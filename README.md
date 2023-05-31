# ubuntu steam cache pre-build/setup

this is a steam cache setup for a ubunutu os.

the setup only requires to clone the repository & run the bash/sh file named **init_cache.sh**

## 1.
  (Optional but recommened)
  - add a seperate user with admin privilages to run the docker containers & and commands
  - run the followling commands to do so, **if not skip to step **2****
  ```
  ~$ sudo adduser USERNAME
  ```
  ```
  ~$ usermod -aG sudo USERNAME
  ```
  ```
  ~$ sudo adduser USERNAME
  ```


## 2. 
  - cd into the steam cache directory
  ```
  ~$ cd steam_cache
  ```
  - run the following command 
  ```
  ~$ chmod +x init_cache.sh
  ```
  if admin priviliges needed run **sudo** /  or be in **root**
