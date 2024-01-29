<h1>Implementing a serverless reminder application</h1>

<h2>Description</h2>
This project showcases the construction of a serverless reminder application, illustrating the step-by-step process of its development. The application is designed to be loaded from an S3 bucket and executed in a browser, establishing communication with Lambda and Step Functions through an API gateway endpoint. By delving into this demonstration, viewers gain insights into the intricacies of building a serverless application that seamlessly integrates components like S3, Lambda, Step Functions, and API Gateway. This hands-on guide offers a practical understanding of how these serverless elements collaborate to create a functional and dynamic reminder application in a browser environment.
<br />


<h2>Services Used</h2>

- <b>S3</b>
- <b>IAM</b> 
- <b>Lambda</b>
- <b>Step Functions</b> 
- <b>API gateway</b>

<h2>Environments Used </h2>

- <b>AWS</b>

<h2>Program walk-through:</h2>
<H3>Step 1 - Create and verify SES application sending email address</H3>
<img src="https://i.imgur.com/gP5PXr9.png" height="60%" width="60%" alt="Image 1"/>



<H3>Step 2 - Create email reminder lambda function</H3>
<img src="https://i.imgur.com/BCNR1CN.png" height="60%" width="60%" alt="Image 2"/>



<H3>Step 3 - Create state machine</H3>
<img src="https://i.imgur.com/6PbtXs9.png" height="60%" width="60%" alt="Image 2"/>

<H3>Step 4 - Create API Lambda function</H3>
<img src="https://i.imgur.com/xfQG9QU.png" height="60%" width="60%" alt="Image 2"/>


<H3>Step 5 - Create API</H3>
<img src="https://i.imgur.com/MTTxph2.png" height="60%" width="60%" alt="Image 2"/>

<H3>Step 6 - Create S3 bucket</H3>
<img src="https://i.imgur.com/tPwQ8wt.png" height="60%" width="60%" alt="Image 2"/>



<h2>Successfully reminder notification</h2>

<img src="https://i.imgur.com/b34894K.png" height="80%" width="80%" alt="Image 1"/>

<h2>YouTube Demonstration </h2>

[Implementing a serverless reminder application](https://www.youtube.com/watch?v=wvtcEZW87r0)



</p>
