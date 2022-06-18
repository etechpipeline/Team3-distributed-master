How to rescue a crashing Jenkins master instance.
  1. spin up an new Jenkins server
  2. Install the job import plugin in the Jenkins UI pluggins
  3. Navigate to mangage>global settings>configuration
  4. configure the Job Import Plugging by adding the URL of the Old Jenkins Server
  5. Asign a cridentails and the cridentails shold be the cridentails of the ui of the old Jenkins
  6. create cridentails> username(old Jenkins server name)> Password> ID> Description>Add>save
  7. After all the configuration is complete, The New server will now have access to the old server.


What is the use of thinBackup plugin and how have you used it to perform backup configurations
  1. ThinBackup plugging is use to configure back up of a Jenkins server to recover critical configuration file incase the jenkins server crashes.
  2. Use the thin Backupplugin to configure backup of a Jenkins server
  3  Recover configuration files incase the Jenkins server crashes. 
  4. Extend the NFS sever 
  5. Configure for Stronger Backup
