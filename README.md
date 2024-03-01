### SD540 Workshop 01 (Email/SMS, and environment variables)
  
Environment variables hold secret keys and sensitive configuration data that we prefer to keep in a safe place. They are usually accessed from the `process.env` global object.
  
In this workshop, you will update yesterday’s homework to send you an email with the following body:
```
From: Thumbnail Generator App
Subject: Status Report
Body: 
This is an automated email. 
The input folder has 31 thumbnails.
The output folder has 31 thumbnails.
Generated 0 new thumbnails. 
```
Use the [dotenv](https://www.npmjs.com/package/dotenv) module to save environment variables.  
Use the [@sendgrid/mail](https://www.npmjs.com/package/@sendgrid/mail) module and integrate it with your application to send the status email.
