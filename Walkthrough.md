Starting with the S3, we’ll create a bucket using a globally unique name. We’ll use the bucket to store our email template and list of email addresses. I have provided an email template and a CSV as an example, but you will have to replace the email addresses with working ones such as your own. 
You can drag and drop the files into the s3 bucket or upload them. 

Now that we have the email stored, we need to be able to send it. We’ll be using SES. For this step, you will need to have a domain. SES will ask for you to verify ownership of a domain. You can buy one from goddady, domain.com, bluehost, hostinger, and many more. 

When verifying, you must copy the CNAME records to publish to your domain’s DNS provider. Doing this quickly is great since it can take up to 72 hours to detect and authenticate.


