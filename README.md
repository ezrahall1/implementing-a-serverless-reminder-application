<h1>Implementing a serverless reminder application</h1>

<h2>Description</h2>

In this project I will be demonstrating how I built a serverless reminder application. The application will load from an S3 bucket and run in a browser communicating with Lambda and Step Functions via an API gateway endpoint using the application.

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
<img src="https://i.imgur.com/BCNR1CN.png" height="70%" width="70%" alt="Image 2"/>



<H3>Step 3 - Create state machine</H3>
<img src="https://i.imgur.com/6PbtXs9.png" height="80%" width="80%" alt="Image 2"/>

<H3>Step 4 - Create API Lambda function</H3>
<img src="https://i.imgur.com/xfQG9QU.png" height="80%" width="80%" alt="Image 2"/>


<H3>Step 5 - Create API</H3>
<img src="https://i.imgur.com/MTTxph2.png" height="80%" width="80%" alt="Image 2"/>

<H3>Step 6 - Create S3 bucket</H3>
<img src="https://i.imgur.com/tPwQ8wt.png" height="80%" width="80%" alt="Image 2"/>



<h2>Successfully reminder notification</h2>

<img src="https://i.imgur.com/b34894K.png" height="80%" width="80%" alt="Image 1"/>

<h2>YouTube Demonstration </h2>

[Implementing a serverless reminder application](https://www.youtube.com/watch?v=wvtcEZW87r0)



</p>
