git clone -b main https://github.com/anshulc55/ansible_automation.git

sudo apt-get -y install openjdk-8-jdk openjdk-8-jre

java --version

printenv

cat >> /etc/environment <<EOL 
                              
JAVE_HOME=/usr/lib/jvm/java-8-openjdk-amd64

JRE_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre                              

EOL  
                              
reboot
                              
printenv
                              
                              
