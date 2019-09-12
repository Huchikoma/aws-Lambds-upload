此项目是基于AWS lambds + S3 + API Gateway的无服务器程序

实现了选择并上传文件至S3 Bucket，并且支持S3中文件的下载

Deploy
Prerequisites: Node.js and AWS CLI installed

Create an AWS Account and IAM User
aws configure
//suggest set us-east-1 but cn-north-1
export CODE_BUCKET=bucket
export DEST_BUCKET=bucket
npm install
npm run build
npm run package
npm run deploy

demo:https://m2hqwsu70g.execute-api.ap-northeast-1.amazonaws.com/Prod

reference
https://edu.51cto.com/center/course/lesson/index?id=211315
https://www.netlify.com/blog/2016/11/17/serverless-file-uploads/