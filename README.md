# jenkins_blog
reference repo:   https://github.com/archerysec/jenkins_blog.git
IN this project is R&D about docker container security scanning purpose, in here i have include archerysec (Vulnerability Management) [in this project i don't use it.]. 
i used jenkins and Anchore Engine (opensource ver) only.

Note: 
 - you need install docker in jenink docker container (i may update create jenkins image which have docker instlalled)
 - chmod 666 /var/run/docker.sock - for allow jenkins have permission rw for docker (able to use docker command)
 - create jenkins_home folder for persistent jenkins home
 - install anchore enine jenkins plugin 
