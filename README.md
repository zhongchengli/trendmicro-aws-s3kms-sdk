# Trend Micro Aws S3-KMS library
![](https://img.shields.io/node/v/mocha)
![code size](https://img.shields.io/github/languages/code-size/zhongchengli/trendmicro-aws-s3kms-sdk)
![aws-sdk](https://img.shields.io/npm/l/aws-sdk)
![mocha](https://img.shields.io/npm/l/mocha)
![dotenv](https://img.shields.io/npm/l/dotenv)


# Description

In this round of Trend Micro’s hiring process. Trend Micro would like to assess candidates' technical skills with an exercise that should take a few hours. Trend Micro wants to be respectful to your time and an exercise can save multiple interviews.

# Exercise

## Backend Project:
AWS S3 + KMS

## Requirements:

1. [X] Create a Node.js library to download all objects in a given S3 bucket and save them locally, maintaining directory structure.
2. [?] Control concurrency to keep at most four parallel downloads in progress.
Hint: You can use Bluebird promise library.
3. [X] Create a file containing the list of downloaded files then encrypt this file using KMS with a user-defined CMK and save it locally.
4. [X] Write unit tests for your code by mocking AWS S3 API.
Hint: You can use the aws-sdk-mock npm module
5. [X] Produce a code coverage report for your test suite.
6. [X] Write an integration test to demonstrate full functionality of code.