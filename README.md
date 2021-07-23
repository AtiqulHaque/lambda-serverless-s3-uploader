# lambda-serverless-s3-uploader

This package is use for upload image to s3 bucket through lambda serverless function

Install npm packages

Step 1: npm install -g serverless

Step 2: npm Install

Step 3: serverless deploy

With aws profile

serverless deploy --aws-profile profileName

Invoking the function

curl -H "Content-type: application/json" -d '{"photoUrl":"https://devclass.com/wp-content/uploads/2018/10/lambda-696x387.jpeg"}' 'https://5iki4ugmfg.execute-api.ap-southeast-1.amazonaws.com/dev/upload'
