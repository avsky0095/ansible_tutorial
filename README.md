# ansible_tutorial

Setup ansible for learning purpose

initial ansible repo


main files:
- inventory		 contains ip address for servers
- ansible.cfg	 contains ansible configurations 
- site.yml		 main ansible playbook tasks

folders:
- roles			 contains separated playbooks from site.yml in order to more clean code
  > tasks		 main script of tasks	 				 
  > handlers	 separate task in more specific ways
  > files		 additional files for tasks
- host_vars		 additional variable for server for specific tasks

etc:
- bootstrap.yml	 initial configuration for fresh new server

