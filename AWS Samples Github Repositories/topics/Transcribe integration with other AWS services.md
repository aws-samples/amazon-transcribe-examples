

## Transcribe integration with other AWS services

1. [AWS Augmentability](https://github.com/aws-samples/aws-augmentability)

AWS AugmentAbility is a mobile web app which showcases 5 AWS AI services (Amazon Transcribe, Amazon Translate, Amazon Polly, Amazon Rekognition and Amazon Textract) and, at the same time, provides features that may benefit people with a visual or communication impairment, including difficulties in reading written text (text recognition), hearing (live transcription), speaking (text-to-speech), or having a conversation in a foreign language (voice-to-voice live translation).

2. [Amazon Transcribe Comprehend Podcast](https://github.com/aws-samples/amazon-transcribe-comprehend-podcast)

A demo application that transcribes and indexes podcast episodes so the listeners can explore and discover episodes of interest and podcast owners can do analytics on the content over time. This solution leverages Amazon Transcribe, Amazon Comprehend, Amazon Elasticsearch, AWS Step Functions and AWS Lambda.

3. [Realtime Toxicity Detection](https://github.com/aws-samples/realtime-toxicity-detection)

This repository contains a complete solution for detecting toxicity across voice and text chats, cost efficiently and at scale, in near real time. It makes use of a number of Serverless and Fully Managaed AWS services, including Amazon SageMaker, Amazon Cognito, AWS Lambda, AWS Amplify, and Amazon Transcribe. Whilst it uses Artificial Intelligence (AI) and Machine Learning (ML) services, it requires no expert knowledge in these domains.

4. [Amazon Live translation polly transcribe](https://github.com/aws-samples/amazon-live-translation-polly-transcribe)

In this post, you will learn how to use three fully managed AWS services (Amazon Transcribe, Amazon Translate, and Amazon Polly to produce a near-real-time speech-to-speech translator solution that can quickly translate a source speaker’s live voice input into a spoken, accurate, translated target language, all with zero machine learning (ML) experience.

5. [Amazon Transcribe Video Conferencing Tool](https://github.com/aws-samples/amazon-transcribe-video-conferencing-tool)

This repo contain the CloudFormation templates required to deploy a solution with the following capabilities:

5.1 Transcribe a video input
5.2 Redact personally identifiable information and remove it from the transcript
5.3 Process the input file to mute personally identifiable information
5.4 Generate a non-extractive video summary

6. [Amazon Transcribe & Email Integration](https://github.com/aws-samples/amazon-transcribe-email-workflow)

This PoC shows how can an audio file be converted to text using a simple Email workflow. A user can record an audio on their smart phone and send it to an email inbox as an attachment. Some back-end service monitoring that Inbox gets an "email-received" notification and sends the audio file to the Transcribe service for the transcription. Once the ASR process completes, the response text file is then emailed as an attachment to the sender.

7. [S3 - Auto-transcriber and sentiment analyzer](https://github.com/aws-samples/amazon-s3-auto-transcriber-sentiment-analyzer)

The S3 Auto-transcriber and sentiment analyzer will automatically convert uploaded MP3 files into transcribed text, using Amazon Transcribe. The resulting text is used to run a sentiment analysis with AWS Comprehend, and then store the result in DynamoDB.

8. [Amazon Transcribe News Media Analysis](https://github.com/aws-samples/amazon-transcribe-news-media-analysis)

This solution allows you to create transcriptions of live streaming video using AWS Transcribe. The application consists of a Web UI where the user may submit URLs of videos for processing, which in turn creates an ECS task per URL running in Fargate to begin the transcription. A user can then view the video and follow the text in real time by clicking on the link provided by the UI.

9. [Amazon IVS Auto-captions Web demo](https://github.com/aws-samples/amazon-ivs-auto-captions-web-demo)

A demo web application for demonstrating how you can use Amazon IVS in conjunction with Amazon Transcribe to deliver real-time captions for live streams. This demo also shows how Amazon Translate can be used to deliver auto-translated captions to viewers (optional during deployment).

10. [Video metadata extraction and knowledge graph](https://github.com/aws-samples/aws-video-metadata-knowledge-graph-workshop)

This repository contains a series of 4 jupyter notebooks demonstrating how AWS AI Services like Amazon Rekognition, Amazon Transcribe and Amazon Comprehend can help you extract valuable metadata from your video assets and store that information in a Graph database like Amazon Neptune for maximum query performance and flexibility. At the end of the workshop you'll typically be able to search for a specific label or entity and return a list of 1min video segments related to your search across your videos.

11. [AWS VOD Captioning using AWS Transcribe](https://github.com/aws-samples/aws-transcribe-captioning-tools)

If you just want to create an SRT or a VTT file, the tools directory contains Python code to convert AWS Transcribe JSON to an SRT or a VTT file. These files can be imported and used on web or desktop video players.

12. [Amazon Transcribe and Comprehend using event sourcing](https://github.com/aws-samples/transcribe-comprehend-quicksight-demo)

In this demo we are going to create a process pipeline to transcribe audio files and later on process sentiment analysis over the transcriptions. This demo uses the "Event Sourcing" pattern to provide a scalable and cost-efficient solution. The language for processing is spanish by default, you can change it in the SAM template.








