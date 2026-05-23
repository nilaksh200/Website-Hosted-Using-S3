<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Host a Website on Amazon S3

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-host-a-website-on-s3)

**Author:** Nilaksh Pathak  
**Email:** nilaksh2004@gmail.com

---

![Image](http://learn.nextwork.org/exuberant_vermilion_joyful_penguin/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate... I'm doing this project to learn how to host website using s3 and use bucket policies

### Tools and concepts

Services I used were S3 storage, bucket policy, ACL

### Time, challenges, and wins

This project took me approximately 1 hr

---

## How I Set Up an S3 Bucket

### What I did in this step

In this step, I am creating a storage space for my website's files

### How long it took to create the bucket

Creating an1m S3 bucket took me...
1minute

### Region selection

The Region I picked for my S3 bucket was mumbai as its the closest

### Understanding bucket name uniqueness

S3 bucket names are globally unique! This mean no one else can use the same s3 bucket name unless one deletes it

![Image](http://learn.nextwork.org/exuberant_vermilion_joyful_penguin/uploads/aws-host-a-website-on-s3_ba6d42ad)

---

## Upload Website Files to S3

### What I did in this step

In this step, I will upload all the files of my website and the folder

### Files I uploaded

I uploaded two files to my S3 bucket - they were index.html and other was a folder consisting of all the icons, css styles etc.

### How the files work together

Both files are necessaory for this project as index is the default route i.e it should open up first and the other folder includes all the icons, css styles etc for the website

![Image](http://learn.nextwork.org/exuberant_vermilion_joyful_penguin/uploads/aws-host-a-website-on-s3_a265af88)

---

## Static Website Hosting on S3

### What I did in this step

In this step, I will configure s3 bucket for static website hosting so I can host it

### Understanding website hosting

Website hosting means hosting your website online on the net

### How I enabled website hosting

To enable website hosting with my S3 bucket, I provisioned static website hosting as enabled

### Access Control Lists (ACLs)

An ACL is used so people can invidiually make changesm enabled acls

![Image](http://learn.nextwork.org/exuberant_vermilion_joyful_penguin/uploads/aws-host-a-website-on-s3_c22c54c0)

---

## Bucket Endpoints

### Understanding bucket endpoint URLs

Once static website is enabled, S3 produces a bucket endpoint URL, which is used as a link for the website

### What I saw when I tested the endpoint

When I first visited the bucket endpoint URL, I saw... The reason for this error was forgot

![Image](http://learn.nextwork.org/exuberant_vermilion_joyful_penguin/uploads/aws-host-a-website-on-s3_22ce4daf)

---

## Success!

### What I did in this step

In this step, I will... because...

### How I resolved the 403 error

To resolve this 403 Forbidden error, I follow these rivers

![Image](http://learn.nextwork.org/exuberant_vermilion_joyful_penguin/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Bucket Policies

### What I did in this extension

In this project extension I'm about to use bucket policies so that no indiviual person can delete the s3 object index.html 

### Understanding bucket policies

An alternative to ACLs are bucket policies, which are... The benefit of using bucket policies is more secure  while ACLs are useful for...

![Image](http://learn.nextwork.org/exuberant_vermilion_joyful_penguin/uploads/aws-host-a-website-on-s3_sm2sm2sm)

### What my bucket policy does

My bucket policy when enabled doesnt let any other user delete s3 bucket file

---

---
