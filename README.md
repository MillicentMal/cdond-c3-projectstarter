
## Give Application Auto-Deploy Superpowers (Udacity Cloud DevOps Engineering Project)
This project, is proof of mastery of the following learning objectives:

- Explain the fundamentals and benefits of CI/CD to achieve, build, and deploy automation for cloud-based software products.
- Utilize Deployment Strategies to design and build CI/CD pipelines that support Continuous Delivery processes.
- Utilize a configuration management tool to accomplish deployment to cloud-based servers.
- Surface critical server errors for diagnosis using centralized structured logging.

![Diagram of CI/CD Pipeline we will be building.](udapeople.png)

### Instructions

* [Selling CI/CD](instructions/0-selling-cicd.md)
* [Getting Started](instructions/1-getting-started.md)
* [Deploying Working, Trustworthy Software](instructions/2-deploying-trustworthy-code.md)
* [Configuration Management](instructions/3-configuration-management.md)
* [Turn Errors into Sirens](instructions/4-turn-errors-into-sirens.md)

### Project Submission

### URLS FOR SUCCESSFUL DEPLOYMENT

The URL Screenshots represent the complete project output. 
1. Showing the S3 Bucket working
 ![URL01](screenshots/URL02_SCREENSHOT.png)
2. Cloudfront distribution URL
 ![URL02](screenshots/URL03_SCREENSHOT.png)
 3. Backend URL
  ![URL03](screenshots/URL04_SCREENSHOT.png)
4. Promethus monitoring server
![URL04](screenshots/URL05_SCREENSHOT.png)


  1. Job failed because of compile errors. 
 ![SCREENSHOT01](screenshots/SCREENSHOT01.png)
  2. Job failed because of unit tests.
  ![SCREENSHOT02](screenshots/SCREENSHOT02.png)
  3. Job that failed because of vulnerable packages. 
  ![SCREENSHOT03](screenshots/SCREENSHOT03.png)
 4. An alert from one of your failed builds. 
  ![SCREENSHOT04](screenshots/SCREENSHOT04.png)
  5. Appropriate job failure for infrastructure creation. 
  ![SCREENSHOT05](screenshots/SCREENSHOT05.png)
  6. Appropriate job failure for the smoke test job.
  ![SCREENSHOT06](screenshots/SCREENSHOT06.png)
  7. Successful rollback after a failed smoke test. 
  ![SCREENSHOT07](screenshots/SCREENSHOT07.png)
  8. Successful promotion job. 
  ![SCREENSHOT08](screenshots/SCREENSHOT08.png)
  9. Successful cleanup job. 
  ![SCREENSHOT09](screenshots/SCREENSHOT09.png)
  10. Only deploy on pushed to `master` branch. 
  ![SCREENSHOT10](screenshots/SCREENSHOT10.png)
  11. Provide a screenshot of a graph of your EC2 instance including available memory, available disk space, and CPU usage.
  ![SCREENSHOT11- free memory](screenshots/SCREENSHOT11-free-memory.png)
   ![SCREENSHOT11- disk space](screenshots/SCREENSHOT11-total-memory.png)
   ![SCREENSHOT11- CPUGraph](screenshots/SCREENSHOT11_CPUGRAPH.png)

  1. Provide a screenshot of an alert that was sent by Prometheus.
  ![SCREENSHOT12](screenshots/SCREENSHOT12.png)





- Your presentation should be in PDF format named "presentation.pdf" and should be included in your code repository root folder. 

Before you submit your project, please check your work against the project rubric. If you haven’t satisfied each criterion in the rubric, then revise your work so that you have met all the requirements. 

### Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool

### License

[License](LICENSE.md)


