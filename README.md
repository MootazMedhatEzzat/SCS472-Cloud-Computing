# SCS472-Jenkins-Lab-Task

# Team members
- Mootaz Medhat Ezzat Abdelwahab    (20206074)

# Task 1
- http://localhost:3000/api/signup
- http://localhost:3000/api/signin
- http://localhost:3000/api/doctors/addslot
- http://localhost:3000/api/doctors/cancelslot
- http://localhost:3000/api/doctors/slots/:id
- http://localhost:3000/api/patients/:id/getslots
- http://localhost:3000/api/patients/bookappointment
- http://localhost:3000/api/patients/updateappointment
- http://localhost:3000/api/patients/cancelappointment
- http://localhost:3000/api/patients/:id/reservations

# Task 2
- Create a bash script file that executes the “ls” command
- Push the bash file into a newly created repo
- Create a new pipeline item on jenkins
![image](https://github.com/MootazMedhatEzzat/JenkinsLabTask/assets/97257822/bd373264-0d2f-4d80-811b-80e72bffe2d9)

- 
  - `cd clinicWebApp/client`
  - `npm run build`
  - `node server.js`
- In the seconde terminal, run:
  - `cd clinicWebApp/server`
  - `node server.js`
