OpenCV python 3
===============

Ansible role to install Opencv 3 for python.

Requirements
------------
 - python3
 - pip3
 - ansible

Role Variables
--------------

- **install_dir: /home/pi** -> Directory to install OpenCV
- **oepncv_url: "https://github.com/Itseez/opencv/archive/3.3.0.zip"** -> Download URL for opencv
- **opencv_contrib: "https://github.com/Itseez/opencv_contrib/archive/3.3.0.zip"** -> Extra modules for SIFT and SURF

Example Playbook
----------------
Run the following command to install opencv via this playbook

`ansible-playbook opencv.yaml -i <path_to_hosts_file> --ask-become-pass -e "host_name=<name of the host block in hosts file>"`

NOTE
----
This script will take areound 4 hours to complete, so while this is running go watch a movie or have lunch / dinner :P
