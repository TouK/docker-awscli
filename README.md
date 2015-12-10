# docker-awscli

##Example - Copy file to S3
```docker run -e AWS_ACCESS_KEY_ID=<key_id> -e AWS_SECRET_ACCESS_KEY=<access_key> -e REGION=<> -v $PWD:/s3 touk/awscli s3 cp some.file s3://my_bucket/```
