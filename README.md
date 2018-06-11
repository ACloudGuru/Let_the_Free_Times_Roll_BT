# Let_the_Free_Times_Roll_BT
An A Cloud Guru Maker Lab - 
Let the Free Times Roll - Using AWS Continuous Deployment tools.

Manually uploading and deploying code to update applications is a thing of the past. Using AWS tools like CodePipeline, CodeBuild, & S3 students will build a system that allows them to write and push code that triggers seamless and automatic deployments. Students will also setup an email notification that is sent to developers if a status change is made in the build process using CloudWatch & SNS. Let the free times roll with Continuous Deployments.

Prepared by [Brock Tubre](https://brocktubre.com) 2018

Lab files for A Cloud Guru, Maker Lab - Let the Free Times Roll

## Development server

Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `npm run build -prod` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Deploy
Using CodePipeline and CodeBuild we will configure the buildspec.yml in the root directory to deploy our build artificats to S3 using `aws s3 sync`.

## What is covered?
- Setting up Github Repository
  - Fork A Cloud Guru, Maker Lab - Let the Free Times Roll repository code
  - Push code to new personal repository

- Setting up a CodePipeline
  - Configure a new CodePipeline with CodeBuild

- Setting up a CodeBuild
  - Configuring a new CodeBuild

- Setting up S3
  - Setting up S3 bucket for static hosting
  - Attach policy to IAM role

- View live Application

- Setting up CloudWatch event and SNS Topic
  - Create and subscribe to an SNS topic
  - Configure CloudWatch event to trigger on status changes in CodeBuild
  - See emails sent to subscribers to SNS topic

Please note, this is provided as-is, neither I, nor A Cloud Guru support this code. If you do identify any errors, then please identify and we will attempt to fix on a best efforts basis.

IMPORTANT - We recommend creating a new account or lab spece for this workshop. Using an existing account could cause damage or disruption to the resources in that account.



## IMPORTANT
These files are distributed on an AS IS BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied


## June 2018
Initial Creation.

