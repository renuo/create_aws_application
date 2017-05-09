

Creates a series of buckets on Amazon S3 which follow the Renuo Standard Flow.

By default three buckets application_name-master, application_name-develop and application_name-testing are created.

Edit the script to change the default behaviour.


You can execute running:

    ./aws_create_application application_name [aws profile] [policy name]

The script will print the AWS credentials to access each bucket.

A CloudFront distribution will be created in front of each bucket as well.
