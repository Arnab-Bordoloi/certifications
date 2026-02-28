# AI Managed Services of AWS

## Participants
- Comprehend
- Translate
- Textract
- Rekognition
- Kendra
- Lex
- Polly
- Transcribe
- Personalize
- Sagemaker

|SlNo.|Area|Participant|Superpowers|Examples|
|-----|----|-----------|-----------|--------|
|1|Text & Docs|Comprehend|NLP,managed and serverless,find language of text, gets key phrases, places, people, brands, or events, +ve/-ve sentiments, use ML, tokenize, parts of speech, group files based on topics|sentiments analysis from customer emails, group articles by topics, training data in S3 and Comprehend can train and classify like this looks like a complaint document, can do NER (Named Entity Recognition). e.g., extract policy number|
|2|Text & Docs|Translate|
|3|Text & Docs|Textract|
|4|Vision|Rekognition| Identify objects|Lebelling, Content moderation, test detection, face detection, pathing| find logos or harmful images. A2I (Augmented AI) for human review. user-> chatbot who gen images -> send to rekog to see if image is not harmful
|5|Search|Kendra|
|6|Chatbots|Lex|
|7|Speech|Polly|opposite of Transcribe, voice from text, Lexicons like pronounce AWS as Amazon Web Services, SSML (Speech markup language like <break> puts a long pause)| Speech mark i.e., highlight as it is speaking
|8|Speech|Transcribe|speech into text. uses ASR (Automatic Speech Recognition) a deep learning process, removes PII (redaction),multi lingual. We can improve accuracy of transcribe by feeding custom vocabularies| subtitles, transcribe customer service calls, get metadata of media assets, toxicity detection|
|9|Recommendation|Personalize|

## Superpowers
- Pre-trained ML services
- Multi AZ and multi regions (availability)
- CPU & GPUs for specific use-cases
- Token based (pay for what is used)
- Provisioned throughput for predictable workloads

