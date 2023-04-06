## Transcribe Medical

1. [Medical Transcription Analysis](https://github.com/aws-samples/medical-transcription-analysis)

Medical Transcription Analysis (MTA) is a simple solution that leverages the powers of Amazon Transcribe Medical and Amazon Comprehend Medical to provide medical notes transcription and comprehension. The solution opens a WebSocket between the client (browser) and Amazon Transcribe Medical. This WebSocket is used to send the audio from the client to Amazon Transcribe Medical and retrieve real time transcription which is then rendered on the UI. The transcribed results are then sent to Amazon Comprehend Medical which returns an analysis of the transcription.