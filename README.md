# ansible-gitlab-ce
Ansible role for install Gitlab CE

## Usage
`> ansible-playbook gitlab.yml -t reconfig -e reconfig=true`

## Example playbook
	- hosts: servers
		- role: john-devops.gitlab-ce
    	tags: gitlab 

## Default variables
**defaults/main.yml:**  
`gitlab_address: gitlab.local`

## ToDo
Create ticket by email
