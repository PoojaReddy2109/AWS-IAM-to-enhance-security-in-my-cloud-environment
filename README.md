# AWS-IAM-to-enhance-security-in-my-cloud-environment
<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Cloud Security with AWS IAM

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-security-iam)

**Author:** poojareddynandhigama@gmail.com  
**Email:** poojareddynandhigama@gmail.com

---

![Image](http://learn.nextwork.org/satisfied_magenta_zany_pawpaw/uploads/aws-security-iam_1c864649)

---

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate kickstart my portfolio using AWS. I'm doing this project to learn about AWS, how we use in real world.

### Tools and concepts

Services I used were... EC2 instance Key concepts I learnt include creating User group and IAM users

### Project reflection

This project took me approximately 2hrs The most challenging part was... stoping the instance It was most rewarding to... creating to user accounts

---

## Tags

### What I did in this step

In this step, I will launch 2 Amazon EC2 instances because to increase Nextwork's computing power. 

### Understanding tags

Tags are like lables, they are usefull to find all resourses with the same tag at once

### My tag configuration

The tag I’ve used on my EC2 instances is called Key Pair The value I’ve assigned for my instances are... Production and Development

![Image](http://learn.nextwork.org/satisfied_magenta_zany_pawpaw/uploads/aws-security-iam_2e0e5a5d)

---

## IAM Policies

### What I did in this step

In this step, I will create IAM policy that gives access to the development instance because if they accidentally shutdown the platform that shoudnot effect on Production environment

### Understanding IAM policies

IAM Policies are the rule for who can do and what with your AWS resourses. giving permission to IAM users

### The policy I set up

For this project, I’ve set up a policy using JSON

### Policy effect

I’ve created a policy that interns will get access only to the develpment environment

### Understanding Effect, Action, and Resource

The Effect, Action, and Resource attributes of a JSON policy means it Allow or deny the action, for resources does this policy specify

---

## My JSON Policy

![Image](http://learn.nextwork.org/satisfied_magenta_zany_pawpaw/uploads/aws-security-iam_1c864649)

---

## Account Alias

### What I did in this step

In this step, I will create AWS Account Alias because it simplify user login to AWS account

### Understanding account aliases

An account alias is the friendly name of your AWS account

### Setting up my account alias

Creating an account alias took me 2mints Now, my new AWS console sign-in URL is https://pooja09.signin.aws.amazon.com/console

![Image](http://learn.nextwork.org/satisfied_magenta_zany_pawpaw/uploads/aws-security-iam_0eb4439b)

---

## IAM Users and User Groups

### What I did in this step

In this step, I will create IAM users and user groups because making interns to login.

### Understanding user groups

IAM user groups are nextwork-dev-group giving access to all users to the AWS resourses at a time

### Attaching policies to user groups

I attached the policy I created to this user group, which means giving access to all users to the AWS resourses at a time

### Understanding IAM users

IAM users are the all interns of development team, they get access only for the development department. 

---

## Logging in as an IAM User

### Sharing sign-in details

The first way is just share your account details with them. After all, you have access to the production instance, which they shouldn't get access to.

### Observations from the IAM user dashboard

Once I logged in as my IAM user, I noticed  Access denied to Servicecatalog:listApplications. This was because AWS console will treat you as someone that is starting from 0 again.

![Image](http://learn.nextwork.org/satisfied_magenta_zany_pawpaw/uploads/aws-security-iam_6f2ab446)

---

## Testing IAM Policies

### What I did in this step

In this step, I will test the intern access because wheather they getting access to development instance or not

### Testing policy actions

I tested my JSON IAM policy by instance type stop 

### Stopping the production instance

When I tried to stop the production instance but it failed to stop instance This was because it is not in the state form. 

![Image](http://learn.nextwork.org/satisfied_magenta_zany_pawpaw/uploads/aws-security-iam_0e7a9d6a)

### Stopping the development instance

Next, when I tried to stop the development instance it successfully stopped This was because it is development instance

![Image](http://learn.nextwork.org/satisfied_magenta_zany_pawpaw/uploads/aws-security-iam_1811801c)

---

## IAM Policy Simulator

### Understanding the IAM Policy Simulator

### How I used the simulator

---

---
