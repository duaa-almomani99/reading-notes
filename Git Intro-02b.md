remote repository 
about 90% of version control related work happens in the local repository staging,commiting,viewing,the status of the log , hisstory ... 
(if you only work on your project you will never need to setup aremote repository , but if you sharing data with team you need to setup 
a remote repository) 
* local repository reside on the computers of team member the remote repository are hosted on aserver that accessible for all team member 


which remote url should i use 
* clonning with Https URLs : the https :/ clone URLs are availabe on all repositorys regardless of visibility 
* clonning with ssh URLs : ssh URLs provide access to get repository via ssh , asecure protocol to use these URLs

you must generate an SSH keypair on your computer and add puplic key to your gethup 

Showing Your Remotes
To see which remote servers you have configured, you can run the git remote command.
It lists the shortnames of each remote handle you’ve specified
 If you’ve cloned your repository, you should at least see origin — that is the default name Git gives to the server you cloned from
 
 You can also specify -v, which shows you the URLs that Git has stored for the shortname to be used when reading and writing to that
 remote
 
 

