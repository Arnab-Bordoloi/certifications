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
|3|Text & Docs|Textract|used to extract text, forms, tables, PDFs, images|read DL and give data, fin services like in invoices and reports, health care, medical records, insurance claims, public sectores like tax forms, ID docs, Passports|
|4|Vision|Rekognition| Identify objects|Lebelling, Content moderation, test detection, face detection, pathing| find logos or harmful images. A2I (Augmented AI) for human review. user-> chatbot who gen images -> send to rekog to see if image is not harmful
|5|Search|Kendra|Fully managed document(within) search powered by ML|text, PDF, HTML, PPT, MS Words, FAQs, where is the IT support (1st floor)|
|6|Chatbots|Lex|create chatbots quickly using voice or text, supports multiple languages, lambda/Connect/Comprehend/Kendra, can ask for input parameters| order pizza, book hotels|
|7|Speech|Polly|opposite of Transcribe, voice from text, Lexicons like pronounce AWS as Amazon Web Services, SSML (Speech markup language like <break> puts a long pause)| Speech mark i.e., highlight as it is speaking
|8|Speech|Transcribe|speech into text. uses ASR (Automatic Speech Recognition) a deep learning process, removes PII (redaction),multi lingual. We can improve accuracy of transcribe by feeding custom vocabularies| subtitles, transcribe customer service calls, get metadata of media assets, toxicity detection|
|9|Recommendation|Personalize|build apps with reccomendations
|10|Mechanical Turk|Cloud sourcing marketplace to perform simple human task|humans take up tasks to label images and get paid|
|11|A2I|Augmented AI|human feedbacks if ML does not have confidence|
|12|Amazone Transcribe Medical |||
|13|Amamzon Comprehend Medical||live voice -> kinesis -> transcribe -> comprehend|
|14|Amazon HealthScribe|||


## Superpowers
- Pre-trained ML services
- Multi AZ and multi regions (availability)
- CPU & GPUs for specific use-cases
- Token based (pay for what is used)
- Provisioned throughput for predictable workloads

