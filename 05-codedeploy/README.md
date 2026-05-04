<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Deploy a Web App with CodeDeploy

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-devops-codedeploy-updated)

**Author:** احمد الاسمري  
**Email:** a7md.buy@gmail.com

---

![Image](http://learn.nextwork.org/compassionate_indigo_innocent_camel/uploads/aws-devops-codedeploy-updated_val-27)

---

## Introducing Today's Project!

In this project, I will demonstrate... I'm doing this project to learn...

### Key tools and concepts

Services I used were... Key concepts I learnt include..

### Project reflection

This project took me approximately... The most challenging part was... It was most rewarding to...

This project is part five of a series of DevOps projects where I'm building a CI/CD pipeline! I'll be working on the next project...

---

## Deployment Environment

To set up for CodeDeploy, I launched an EC2 instance and VPC because...

Instead of launching these resources manually, I used... When I need to delete these resources...

Other resources created in this template include... They're also in the template because...

![Image](http://learn.nextwork.org/compassionate_indigo_innocent_camel/uploads/aws-devops-codedeploy-updated_val-5)

---

## Deployment Scripts

Scripts are... To set up CodeDeploy, I also wrote scripts to...

The 'install_dependencies will...

The start_server.sh will...

The stop_server.sh will...

---

## appspec.yml

Then, I wrote an appspec.yml file to... The key sections in appspec.yml are...

I also updated buildspec.yml because...

![Image](http://learn.nextwork.org/compassionate_indigo_innocent_camel/uploads/aws-devops-codedeploy-updated_val-12)

---

## Setting Up CodeDeploy

A deployment group is... A CodeDeploy application is...

To set up a deployment group, you also need to create an IAM role to...

Tags are helpful for... I used the tag... to...

![Image](http://learn.nextwork.org/compassionate_indigo_innocent_camel/uploads/aws-devops-codedeploy-updated_val-18)

---

## Deployment configurations

Another key settings is the deployment configuration, which affects... I used CodeDeployDefault.AllAtOnce, so...

In order to connect... a CodeDeploy Agent is also set up to...

![Image](http://learn.nextwork.org/compassionate_indigo_innocent_camel/uploads/aws-devops-codedeploy-updated_val-20)

---

## Success!

A CodeDeploy deployment is... The difference to a deployment group is...

I had to configure a revision location, which means... My revision location was...

To check that the deployment was a success, I visited... I saw...

![Image](http://learn.nextwork.org/compassionate_indigo_innocent_camel/uploads/aws-devops-codedeploy-updated_val-27)

---

## Disaster Recovery

In a project extension, I decided to... The intentional error I created was... This will cause the deployment to fail because...'

I also enabled rollbacks with this deployment, which means...

Start your answer with 'When my deployment failed, the automatic rollback... because... To actually recover from... I'd have to... In production environments...

![Image](http://learn.nextwork.org/compassionate_indigo_innocent_camel/uploads/aws-devops-codedeploy-updated_rollback-validation-upload)

---

---
