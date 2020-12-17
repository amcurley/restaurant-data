# restaurant-data  

Goal:  
Create a seamless data experience for the owner and chef of the restaurant  

To Do:  
- Take data from the s3 bucket from toast.  
- Load data into my own s3 bucket or other datalake on aws.  
- Format data for tableau.

    AWS Pipeline?:   
    - CloudTrail to trigger step function that runs lambda function that connects S3 Buckets. S3 Kinesis data firehose to Amazon Quicksight.