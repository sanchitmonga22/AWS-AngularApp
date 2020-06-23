# AWS-AngularApp

A very basic angular app that lets the user login and then compare their age, height and income with other users of the app.
This is a very basic app to practise and learn more about different services offered by **Amazon Web Services**.

The app is hosted at **S3** in **AWS** using the **cloudfront** service to optimize the app for the users all around the world. Along with that I also learned how to use your custom domain using the **Route 53** service and host the application on that.
The APIs are created in **Lambda** and are hosted at **API gateway**. Along with that, the user data is being stored at **DynamoDB** which is a noSql database solution provided by AWS.
While creating this app I learned about creating different custom policies and roles using the **IAM** service to grant and restrict the access to the database for each Lambda function.
I also learned about the **CloudWatch** which is a service that helps track the logs for the Lambda functions.
