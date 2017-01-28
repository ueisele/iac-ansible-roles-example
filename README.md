# Ansible Role: OpenJDK #

The Ansible role installs OpenJDK.

### Install with ansible-galaxy ###

Content of the *requirements.yml* file for zookeeper role:

	- src: git+https://bitbucket.org/ueisele/iac-ansible-roles-openjdk
	  version: 1.0.0
	  
Command to install the OpenJDK role form requirements file:	  
	  
	  ansible-galaxy install -r requirements.yml
