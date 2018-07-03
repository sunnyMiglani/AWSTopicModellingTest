# AWSTopicModelingTest
Topic Modelling example using the AWS Comprehend Suite. 

**Goal**: Using the AWS Comprehend Topic Modelling to create a relation between various articles / revision guides on the BBC Bitesize website
that could allow for a relational database that can be queried through alexa! The goal of this repository focuses on uploading files
to the S3 cloud and retrieving the information for when it's done the work.


# References / Documentation
1. This repository uses the Webscraper for the [BBC Bitesize](https://www.bbc.com/education) from [this repository](https://github.com/sunnyMiglani/WebScrapingTest)


## Instructions / Documentation

### Building an S3 Bucket on amazon

 This assumes that you've already done the aws-cli configuration and have setup your .conf files

 The .conf files are global, so they might not be visible in your repo.



 Creating a bucket :  `aws s3 mb s3://<bucket-name>`
 **Note:** The names for the buckets have restrictions of no special characters and no uppercase and no numbers!


 Deleting a bucket : `aws s3 rm s3://<bucket-name>`

 Listing buckets : `aws s3 ls` 

The longer and more detailed instructions [are on the aws cli website](https://docs.aws.amazon.com/cli/latest/userguide/using-s3-commands.html)
