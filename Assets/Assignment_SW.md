# 19CSE447 - Cloud Computing ![](https://img.shields.io/badge/-Live-brightgreen)
![](https://img.shields.io/badge/Batch-20EEE-lightgreen) ![](https://img.shields.io/badge/Batch-20ELC-lightgreen) ![](https://img.shields.io/badge/Batch-20CCE-lightgreen) ![](https://img.shields.io/badge/Batch-20ECE-lightgreen) ![](https://img.shields.io/badge/Batch-20CSE-lightgreen) ![](https://img.shields.io/badge/UG-blue) ![](https://img.shields.io/badge/Subject-Cloud-blue) ![](https://img.shields.io/badge/Subject-Elective-purple)  <br/>
![](https://img.shields.io/badge/Lecture-3-orange)  ![](https://img.shields.io/badge/Credits-3-orange) <br/>
![](https://img.shields.io/badge/Students-61-blue) ![](https://img.shields.io/badge/Course_Outcome_Attainment-TBD-blue) ![](https://img.shields.io/badge/Average_Marks-TBD-blue) ![](https://img.shields.io/badge/Course_Feedback-TBD-blue) 

## Static Website Hosting
- Sign in to AWS Console:
  - Go to the AWS Management Console (https://aws.amazon.com/console/).
  - Sign in to your AWS account.
  - Navigate to Amazon S3:

- From the AWS Management Console, search for and select "S3" or find it under the "Storage" category.
  - Create an S3 Bucket:
  - Click the "Create bucket" button.
  - Choose a globally unique name for your bucket (since bucket names are unique across all of AWS).
  - Select the region closest to you.
  - Click through the initial configuration options without making changes.

- Enable Static Website Hosting:
  - In the bucket you just created, click on the "Properties" tab.
  - Scroll down to find the "Static website hosting" card.
  - Click the "Edit" button to enable static website hosting.
  - Choose "Use this bucket to host a website."
  - Enter the index document (e.g., index.html) and error document (e.g., error.html).

- Access the Website Endpoint:
  - After enabling static website hosting, you'll find the website endpoint URL. It will be something like: http://your-bucket-name.s3-website-your-region.amazonaws.com.
