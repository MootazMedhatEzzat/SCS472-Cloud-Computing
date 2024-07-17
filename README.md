# SCS472-Cloud-Computing-Jenkins-Lab-Task

![image](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/1ce1b4af-e72d-4998-8f9c-4d56e605400d)

---

<div align="center">
  <table width="100%">
    <tr>
      <td align="left"><strong>Name</strong>: Mootaz Medhat Ezzat Abdelwahab</td>
      <td align="right"><strong>Id</strong>: 20206074</td>
    </tr>
    <tr>
      <td align="left"><strong>Program</strong>: Software Engineering</td>
      <td align="right"><strong>Group</strong>: B (S4)</td>
    </tr>
    <tr>
      <td colspan="2" align="center"><strong>Delivered To</strong>: Prof. Fatma Omara</td>
    </tr>
  </table>
</div>

---

# Task 1
- Install jenkins (optional: using docker image)
1. Visit the Jenkins Official Website: https://www.jenkins.io/download/.
2. Download the Jenkins Installer: This will typically be a .msi file.
3. Run the Installer: Double-click it to run the installer and follow the installation wizard.
   
- Complete configuration

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/b2c2fd7c-a6dc-44b9-9c85-e055b270eb2d)

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/9e9e666e-3dbd-4bb7-9862-6474e92d762a)

- Create admin user

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/48bfe23f-0c19-453b-b2be-00fb76eddf5d)

- Create a pipeline that executes and prints “Hello World”

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/eb5317d7-e59c-455e-9cde-3de552ea8967)

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/9faa2e97-81e5-4221-bee6-931e2223caaa)

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/8ab99c14-47cd-40a3-8c7a-e8230204eaf1)

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/21183fc2-8941-4912-8f51-c69abdcc9224)

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/932ffbf5-6cbf-4aba-a58a-bb7a9931303e)

![image](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/4026019a-3458-4b03-bec1-34c9373f1c95)

# Task 2
- Create a bash script file that executes the “ls” command
- Push the bash file into a newly created repo
- Create a new pipeline item on jenkins

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/be4dfb1f-6e39-4606-a296-5fcec6f19f07)

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/a021d793-7612-4722-b27e-62dd02df7d2c)

In the Pipeline section, you can either write a pipeline script directly or link to a repository. Since i have pushed the script to a repository, i will choose "Pipeline script from SCM" and select the version control system (in our case, Git).

Set the Repository URL.

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/230f9130-c7b7-4aea-8f6c-617d4c84f7ba)

Specify the branch (in our case, main).

Set the Script Path to Jenkinsfile.

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/e1980c61-1282-4157-b9fb-1bd16c03ff08)

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/614328c9-27cd-4dd2-aad9-1b15ba40e95c)

![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/33fd13a4-5177-45bf-970b-9deaa28fba8d)
![unnamed](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/29a8eda1-1f39-40ed-829f-24dfd802d3e8)

- Create a CI/CD for this by configuring jenkins to pull the repo and execute the bash 
In your Git repository, create a file named Jenkinsfile that will include the pipeline script.

___

Now, Jenkins will automatically pull the repository, execute the Bash script, and display the results in the console output.
