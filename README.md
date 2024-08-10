# VoiceScript: AWS-Speech-to-Text-Conversion-Service

VoiceScript is a robust and automated solution for transcribing audio and video files using Amazon Web Services (AWS). This project harnesses the power of AWS Lambda, Amazon S3, and Amazon Transcribe to deliver efficient and reliable transcription services, complete with comprehensive logging and monitoring through Amazon CloudWatch.

## Key Features

#### Seamless Media Upload
Users can effortlessly upload audio or video files to an Amazon S3 bucket, initiating the transcription process.

#### Automated Processing
The upload of a media file automatically triggers an AWS Lambda function, streamlining the transcription workflow.

#### Advanced Transcription
Once triggered, the Lambda function engages Amazon Transcribe to convert spoken content within the media file into accurate text.

#### Comprehensive Log Management
Upon completion of the transcription process, Lambda sends detailed logs to Amazon CloudWatch, facilitating thorough monitoring and debugging.

#### State Monitoring & Management
The change in transcription job state triggers an additional Lambda function, ensuring that all post-transcription processes are executed smoothly and efficiently.

#### Secure Output Storage
The resulting transcription text is securely stored in an Amazon S3 bucket, ready for easy access and further processing.
## Project Tech-Stack

![CloudWatch](Images/CloudWatch.png) 
![S3 Bucket](Images/S3.png)
![Lambda](Images/Lambda.png)
![Transcribe](Images/Transcribe.png)