# configureYum in RHEL 8 and httpd web server using ansible

configure yum repo :

step1:
1.create a folder /dvd1
get from dvd, mount dvd into folder/dvd1
    
step2:
yum conf, dvd folder

step3:
package httpd


Run play book using cmd
[syntax]
ansible-playbook -v [playbookName]
#ansible-playbook -v configureWeb