# jdk_java
nstall Java We will be using open java for our demo, Get latest version from http://openjdk.java.net/install/  yum install java-1.8* #yum -y install java-1.8.0-openjdk Confirm Java Version Lets install java and set the java home  java -version find /usr/lib/jvm/java-1.8* | head -n 3 #JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.191.b12-1.el7_6.x86_64 export JAVA_HOME PATH=$PATH:$JAVA_HOME # To set it permanently update your .bash_profile source ~/.bash_profile
