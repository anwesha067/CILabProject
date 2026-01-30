# CI Lab Project – Complete Terminal Commands Log

This document contains a complete log of all terminal commands executed during the Jenkins CI Lab Project, including installation, configuration, troubleshooting, Git operations, Maven builds, and Jenkins execution.

---

## System & Environment Checks

```bash
pwd
ls
cd ~
cd ~/CILabProject
open .
code .
brew -v
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
java -version
brew install openjdk@17
brew link --force --overwrite openjdk@17
java -version
brew install jenkins-lts
brew services start jenkins-lts
brew services stop jenkins-lts
brew services restart jenkins-lts
brew services list
ls ~/.jenkins
cat ~/.jenkins/secrets/initialAdminPassword
tail -50 ~/.jenkins/jenkins.log
mvn -v
brew install maven
mvn -v
mvn test
mvn clean
mvn clean test
mvn clean package
rm -rf ~/.m2/repository
mvn test
**ping google.com
ping repo.maven.apache.org
nslookup repo.maven.apache.org
sudo dscacheutil -flushcache
sudo killall -HUP mDNSResponder**
git clone https://github.com/anwesha067/CILabProject.git
cd CILabProject
git status
git branch
git log --oneline
mkdir -p src/main/java/com/muj/ci
mkdir -p src/main/resources
mkdir -p src/test/java/com/muj/ci
mkdir scripts
mkdir docker
mv Calculator.java src/main/java/com/muj/ci/
mv CalculatorTest.java src/test/java/com/muj/ci/
nano README.md
nano src/main/java/com/muj/ci/Calculator.java
nano src/test/java/com/muj/ci/CalculatorTest.java
nano scripts/build.sh
nano scripts/deploy.sh
nano Jenkinsfile
nano .gitignore
nano /etc/hosts
chmod +x scripts/build.sh
chmod +x scripts/deploy.sh
ls
rm Readme.md
nano .gitignore
target/
git add README.md
git add src
git add scripts
git add docker
git add pom.xml
git add Jenkinsfile
git add .gitignore
git add -u
git add .
git commit -m "Initial CI lab project setup"
git commit -m "Fix README duplication and documentation"
git commit -m "Restructure project to Maven standard layout"
git commit -m "Remove old root Java files after moving to src structure"
git commit -m "Add terminal commands log for CI lab execution"
git commit -m "Update README documentation"
git pull origin main
git pull --rebase origin main
git rebase --continue
git push origin main
git status
git restore README.md
git reset
brew install tree
tree
mvn clean test
CTRL + C   (stop running command)
CTRL + O   (save file in nano)
CTRL + X   (exit nano)
---


