Lambda Function for Image Resizing

This repository contains the code for a Lambda function designed to automatically resize
images uploaded to an Amazon S3 bucket. The function, written in JavaScript, utilizes the
AWS SDK for JavaScript and the sharp library for image processing.

Features:
Automatically resizes images uploaded to an S3 bucket.
Supports JPEG and PNG image formats.
Efficiently processes images using the sharp library for high-performance image resizing.
Usage:
Clone or download the repository.
Install dependencies using npm install.
Package the function code and dependencies into a ZIP file.
Upload the ZIP file to AWS Lambda.
Configure an S3 trigger to invoke the Lambda function upon new image uploads.

Environment Variables:
DEST_BUCKET: The name of the destination S3 bucket where resized images will be stored.

Folder Structure:
lambda-s3/: Contains the Lambda function code (index.js) and dependencies.
