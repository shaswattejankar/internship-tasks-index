# internship-tasks-index

github repo include codes and readme with used commands

Completed Tasks from Sarveshwar's List -> 18 (+ 4 extra)

1. React app deployment on s3.

2. React app CICD.

3. GitHub workflows for React app. - [link](https://github.com/shaswattejankar/reusable-workflow-test) and [app link](https://github.com/shaswattejankar/react-actions)

4. Installation of web server functionality such as Apache or nginx on EC2.

5. S3 bucket actions using AWS SNS.

6. S3 synchronization of a bucket from one region to another.

7. Static website hosting on S3.

8. Introduction to Docker.

9. Dockerized Python flask application and deployment on EC2. - [link](https://github.com/shaswattejankar/basic-dockerized-flask-app)

10. SDK- Boto3.

11. Implementation of boto3 for various services in aws such as: 
  i) s3 bucket actions 
  ii) IAM
  iii) EC2 , etc.

13. Automation of creating IAM users and assigning IAM groups to users by reading the .yaml file using boto3 - [link](https://github.com/shaswattejankar/create-iam-users-and-groups-yaml)

13. Listing aws lambda functions by extracting JSON.

14. Deploy a Python Hello World app on ec2 instance -[link](https://github.com/shaswattejankar/py-flask-ec2)

15. Github composite-actions on organization repo:
      i)For react WebApp.
    -> Created a composite action to print a hello message, create a build, and deploy with node to s3 bucket where the basic react app is hosted with static site generation link for this: http://actions-bucket.s3-website.us-east-2.amazonaws.com/
    
    [Link to Organisation Repo having React App](https://github.com/githubs-free-organization/react-basic-app)
    
    [Link to Composite Action Repo under same Organization](https://github.com/githubs-free-organization/hello-world-composite-action)

16. GitHub reusable workflows for the React app. Similarly, I created a cid for a basic react app to build and deploy on s3, link: http://reusable-workflows-test.s3-website.us-east-2.amazonaws.com/

    [link to React App repo that uses the "caller workflow"](https://github.com/shaswattejankar/react-actions)

    [link to the Called / Reusable Workflow that is called by the above caller workflow](https://github.com/shaswattejankar/reusable-workflow-test)

17. Maven app deployment on AWS EC2. Built and deployed a basic maven app using Jenkins slave on ec2

    [link to Github Repo](https://github.com/shaswattejankar/hello-world-1/tree/master)

    [Link to temporary ec2 server](http://18.190.154.166:8080/ ) with login: guest and password: guest

18. CICD for spring boot application on aws EC2: 

    i)Github composite-actions

    [link to github repo](https://github.com/shaswattejankar/hello_springboot_composite)

    [link to repo holding the composite action](https://github.com/shaswattejankar/springboot_composite_action)

    ii)GitHub workflows

    [link to github repo](https://github.com/shaswattejankar/springboot-demo)

    [link to repo having the reusable workflow](https://github.com/shaswattejankar/resuable-springboot-workflow)

19. Cron jobs and CPU utilization monitoring.

    i. What are corn jobs, basic cron jobs, and job to log the cpu usage in a log file
    
    ii. Basics of CloudWatch w.r.t ec2 instance, the different types of metrics, and how to creat a alert for when a cpu or disk usage goes above a threshold  for a ec2 instance

20. Boto3 implementation for tasks done in console:

    i. S3 Bucket Actions using AWS SNS. [ Link to repo holding the Code ](https://github.com/shaswattejankar/aws-s3-sns-with-lambda)

    ii. React App Deployment on S3 / Static Site Hosting on S3. [ Link to repo holding the Code ](https://github.com/shaswattejankar/aws-s3-react-app-deployment)

    iii. Static Site deployment on S3 bucket. [ Link to repo holding the code ](https://github.com/shaswattejankar/aws-s3-static-website-deployment-boto3)

    iv. S3 synchronization of a bucket from one region to another. [ Link to repo holding the code ](https://github.com/shaswattejankar/aws-s3-bucket-synchronisation-srr-crr)

    v. Installation of web server functionality of Apache and nginx on a ec2 instance. [ Link to repo holding the code ](https://github.com/shaswattejankar/aws-ec2-nginx-installation-boto3)

    vi. Python flask app deployment on EC2. 

      a. Using already created dockerized python flask app [ Link to repo holding the code ](https://github.com/shaswattejankar/aws-python-flask-docker-ec2)

      b. Using python flask app repository [ Link to repo holding the code ](https://github.com/shaswattejankar/aws-python-flask-github-ec2)

21. What is?: Stateless and Stateful applications, REST API, caching, session management, and Load Balancing (+ with Python web app)

22. Created a boto3 function that encrypts JSON data using an aws kms key, stores the encrypted data locally, uploads it to s3, and decrypts the stored data [ Link to repo holding the code ](https://github.com/shaswattejankar/aws-s3-kms-encrypted-object-upload)

-----
Pending Tasks from Sarveshwar's lists -> 8 :

Only docker and Terraform adv tasks remain
    
8. Maven app deployment on ECS - Fargate

9. 3-tier architecture creation

10. Introduction to terraform.

11. Terraform implementations on various services: 
    i) 3-tier architecture creation using terraform 
    ii) learning the various concepts of terraform. Eg: Data types, variables declaration, loops, implementations infrastructure as a code.

12. Deployment of My Personal Minor Project of Python on EC2.

19. Dockerized LAMP stack application: 
    i) Docker-compose implementation. 
    ii) Dockerfile implementations.

20. Dockerized maven - springboot application.

26. App deployment on ECS - using EC2 and attaching the application load balancer





