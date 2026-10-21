# aws-s3-static-website
A beginner AWS project demonstrating Amazon S3 static website hosting, HTML upload, encryption, and bucket policy configuration.

# AWS S3 Static Website Hosting

## Project Overview
This project demonstrates how to host a static HTML website using Amazon S3. The website displays a simple webpage created with HTML.

## AWS Services Used
- Amazon S3
- S3 Bucket Policy
- Server-Side Encryption with Amazon S3 Managed Keys (SSE-S3)
- Static Website Hosting

## Project Objectives
- Learn how to create an S3 bucket.
- Upload an HTML file to Amazon S3.
- Understand bucket permissions and public access.
- Configure static website hosting.
- Test the website using the S3 website endpoint.
- [AWS S3 Static Website] (aws.preview.png)


## Project Implementation
1. Created an Amazon S3 bucket.
2. Created an HTML webpage named `index.html`.
3. Uploaded the HTML file to the bucket.
4. Checked the bucket's default encryption settings.
5. Enabled static website hosting.
6. Configured a bucket policy to allow public reading of website objects.
7. Opened the website endpoint in a browser and verified that the website was working.

## Website Features
- Simple HTML webpage
- Hosted using Amazon S3
- Accessible through the S3 static website endpoint

## Security Considerations
- Public access was enabled for this demonstration website.
- The bucket should contain only files intended for public viewing.
- AWS access keys, passwords, and other secrets must never be uploaded to GitHub.
- Public access should be disabled when the public demo is no longer needed.
- Encryption settings should be documented according to the actual AWS configuration.

## What I Learned
- Creating and managing S3 buckets
- Uploading objects to Amazon S3
- Configuring static website hosting
- Understanding S3 bucket policies
- Learning about encryption and public access security

## Technologies Used
- Amazon Web Services (AWS)
- Amazon S3
- HTML

## Author
Muqaddus Khan
