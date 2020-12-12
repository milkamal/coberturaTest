# coberturaTest
 2  sudo add-apt-repository ppa:openjdk-r/ppa
    3  sudo apt update
    4  apt search openjdk
    5  sudo apt install openjdk-8-jdk
    6  echo $JAVA_HOME
    7  export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
    8  export PATH=$PATH:$JAVA_HOME/bin
    9  java -version

Maven
 11  sudo apt install -y maven
   12  mvn --version
   13  ls /opt/
   14  export M2_HOME=/usr/share/maven
   15  export MAVEN_HOME=/usr/share/maven
   16  export PATH=${M2_HOME}/bin:${PATH}

mvn test cobertura:cobertura
