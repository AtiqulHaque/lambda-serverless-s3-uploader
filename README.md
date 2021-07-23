# lambda-serverless-s3-uploader

### About

This package is use for upload image to s3 bucket through lambda serverless function

### Install npm packages

Step 1:

```bash
npm install -g serverless

```

Step 2:

```bash
 npm Install

```

Step 3:

```bash
serverless deploy
```

With aws profile

```bash
serverless deploy --aws-profile profileName
```

### Invoking the function

```bash
curl -H "Content-type: application/json" -d '{"photoUrl":"https://devclass.com/wp-content/uploads/2018/10/lambda-696x387.jpeg"}' 'https://5iki4ugmfg.execute-api.ap-southeast-1.amazonaws.com/dev/upload'

```
