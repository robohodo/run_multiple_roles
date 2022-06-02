# run_multiple_roles
The parent repo that will contain code to pull and exec multiple roles. 


I'm trying to create the environment described in this article. 
REF:  https://www.ansible.com/blog/using-ansible-and-ansible-tower-with-shared-roles


The goal is to create a repo that calls and executes roles from 2 other repos. 

Role1 will: 
    1. Create a directory.
    2. Upload some files.
    3. Display the files. 

Role2 will: 
    1. Check for the existence of files created by Role1.
    2. Modify the files.
    3. Display the changes. 

