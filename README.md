# Amazon S3 - practice

Activities present in the Amazon S3 guide, which consist of using basic and static web sites to get, upload and delete files from a simple interface. These web pages will fetch the files hosted in an S3 bucket through the sdk for JavaScript provided by Amazon.

### Configuration 🔧
Create file `./variables-credentials.js` to configure the required credentials for Amazon S3  with the following characteristics:

```properties
var albumBucketName = 'BUCKET_NAME';

// **DO THIS**:
//   Replace this block of code with the sample code located at:
//   Cognito -- Manage Identity Pools -- [identity_pool_name] -- Sample Code -- JavaScript
// Initialize the Amazon Cognito credentials provider
AWS.config.region = 'REGION'; // Region
AWS.config.credentials = new AWS.CognitoIdentityCredentials({
    IdentityPoolId: 'IDENTITY_POOL_ID',
});

```