sudo apt update && sudo apt install openjdk-17(/21 check version)-jdk tomcat10 -y
sudo systemctl status tomcat10
open (http://<public ip>:8080)
sudo apt install maven -y
git clone <YOUR-GITHUB-REPO-URL>
cd SportManagementSystem
mvn clean package
sudo cp target/SportManagementSystem.war /var/lib/tomcat10/webapps/
