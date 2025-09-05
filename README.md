# Mini-Project---Hosting-a-Dynamic-Web-App-on-AWS-with-Terraform-Module-Docker-Amazon-ECR-and-ECS

   Create a new terraform project folder  `mkdir terraform-ec2-webapp`
   <img width="1903" height="522" alt="image" src="https://github.com/user-attachments/assets/7eb7c1fe-706f-4dc6-be40-785f8c7112ff" />

   Enter the location `cd terraform-ec2-webapp`
   <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/9bd6b055-b9d2-4e06-9078-76db34995886" />

   Create directories for the ECR and ECS modules `mkdir -p modules/ecr and mkdir -p modules/ecs`
   <img width="1668" height="450" alt="image" src="https://github.com/user-attachments/assets/3c370b97-05ae-4efa-a783-f23f5c1e50eb" />

   Write your dynamic nodejs web app
   <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/1af75cc4-0fb6-4ae2-bea7-07088399c581" />

   <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/1ce905a0-4cfa-477b-bf57-efe92b03b5fa" />

 Test the application to confirm it is working
 <img width="1264" height="124" alt="image" src="https://github.com/user-attachments/assets/db0418c9-341b-4a60-b4eb-deb1d425e72f" />

 <img width="1920" height="975" alt="image" src="https://github.com/user-attachments/assets/de0d1348-2afa-4503-9bd2-3ffe885825a3" />


   Dockerize your application
   <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/279a3429-908b-435e-85ba-b1c8b2b9310b" />

   Build your docker image
   <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/8a4d1a78-a939-4b8a-89df-6757c99a5b31" />

   <img width="1379" height="255" alt="image" src="https://github.com/user-attachments/assets/614558a0-9125-4324-a902-eb0e37c9e72e" />

   Login to the aws ecr and Tag your docker image
   <img width="1027" height="128" alt="image" src="https://github.com/user-attachments/assets/316df9b6-43ea-445b-b194-9120d3debffd" />

   Create you ECR Repository
   <img width="1920" height="1008" alt="image" src="https://github.com/user-attachments/assets/660edb68-b3ab-41ad-adcc-e21eda58c154" />


   Push you docker image to the ecr repository
  <img width="1511" height="584" alt="image" src="https://github.com/user-attachments/assets/c26c6b2f-1e13-4953-b02b-cd4c3f9e04c6" />

  Check that your docker image has been successfully pushed
  <img width="981" height="272" alt="image" src="https://github.com/user-attachments/assets/a058ae71-038b-4e58-aa78-24693682863f" />

  <img width="1920" height="911" alt="image" src="https://github.com/user-attachments/assets/991e56f4-cf39-4be4-bf94-3cca254811f4" />

  Upon pushing the docker image , through task definition in the ecs terraform file it automatically deploys the application upon passing health checks
  <img width="1916" height="1037" alt="image" src="https://github.com/user-attachments/assets/c6d7f1a8-f120-42f9-9938-34819fcc742f" />

Go to the Load balancer console
<img width="1920" height="911" alt="image" src="https://github.com/user-attachments/assets/d4aa8a80-138d-4289-9093-3e27f7d7245f" />

Copy out the DNS name
<img width="1920" height="911" alt="image" src="https://github.com/user-attachments/assets/c15a1788-32ff-41ca-98a7-c24021caf9ee" />

Access the application on your browser
<img width="1901" height="975" alt="image" src="https://github.com/user-attachments/assets/e52b0ef8-edf5-43a6-84f7-598204341a3c" />









  

   


   







