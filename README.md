# Third-semester-first-assignment---S3-static-web-hosting
Utilizing the AWS S3 bucket and Cloudfront to host a static website

#### The aim of the assignment is to host a static website, using the AWS S3 bucket and Cloudfront to make the contents of the bucket accessible by the public without having to make the S3 bucket public.

## Requirements
1. An AWS account
2. A S3 bucket
3. An AWS cloudfront distribution.

## Steps to do this
1. Create a S3 bucket on the AWS console, after which the newly created S3 bucket will be edited (name the bucket accordingly; with a unique name that has not been previously used by any other AWS user)

![S3 bucket creation](./bucket_creation.png)

2. Ensure you tick on the button that allows your bucket to host a static website while creating your newly created bucket. Also make sure the access to the bucket remains public; set a default home page for the website, which is "index.html" by default and also an error document, which will be the error message that pops up whenever an error occured e.g "404.html"

![edit bucket creation page](./edit_page.png)
![edit_page](./edit_static_website.png)




