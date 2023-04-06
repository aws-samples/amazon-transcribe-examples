### Call analytics

1. [Amazon transcribe post call analytics](https://github.com/aws-samples/amazon-transcribe-post-call-analytics)

This sample solution, Post Call Analytics (PCA), does most of the heavy lifting associated with providing an end-to-end solution that can process call recordings from your existing contact center. PCA provides actionable insights to spot emerging trends, identify agent coaching opportunities, and assess the general sentiment of calls.

2. [Amazon transcribe live call analytics] (https://github.com/aws-samples/amazon-transcribe-live-call-analytics)

Live Call Analytics with Agent Assist (LCA), does most of the heavy lifting associated with providing an end-to-end solution that can plug into your contact center and provide the intelligent insights that you need.

3. [Convert JSON To Word Document] (https://github.com/aws-samples/amazon-transcribe-output-word-document)

This Python3 application will process the results of a synchronous Amazon Transcribe job and will turn it into a Microsoft Word document that contains a turn-by-turn transcript from each speaker. It can handle processing a local JSON output file, or it can dynamically query the Amazon Transcribe service to download the JSON. It works in one of two different modes:

3.1 Call Analytics Mode - using the Call Analytics feature of Amazon Transcribe, the Word document will present all of the analytical data in either a tabular or graphical form

3.2 Standard Mode - this will optionally call Amazon Comprehend to generate sentiment for each turn of the conversation. This mode can handle either speaker-separated or channel-separated audio files
