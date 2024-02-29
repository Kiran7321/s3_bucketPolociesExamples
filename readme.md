# 99.eleven 9's after decimal
That’s the availability aws has promised for this service, well way better than your crush’s reply

- S3 is the 2nd most service introduced by aws
- Each object in a s3 bucket can be up to 5 TB
- For larger files, you can upload using multi parted upload

- S3 ~ simple storage service which is scalable, available, cost effective, performance
- Allows you to create buckets where you can store data
- Objects in s3 buckets are globally accessible and are encrypted by default
- We use bucket policies to allow assess to these buckets which are generally written in JSON

- As you can see below, the s3 objects/content are globally accessiable [top right rectangle]. But as any resource in aws is tied to availability zone [AZ], bucket will be created in chosen AZ

![Screenshot 2024-02-29 at 12 46 07 PM](https://github.com/Kiran7321/s3_bucketPolociesExamples/assets/89258260/57592516-7be4-482a-b7e5-43d3a6bd6e92)

- sample bucket policies will be in 
