<!--This command is used to convert a text file to an mp3 using Amazon Polly. Upload the text file to Amazon S3 then run the AWS Polly command. Once complete you can download the generated mp3 and play it -->



aws polly start-speech-synthesis-task \
          --engine standard \
          --language-code en-AU \
          --output-format mp3 \
          --output-s3-bucket-name <s3-bucket-name> \
          --output-s3-key-prefix <folder/filename.txt> \
          --sample-rate 24000 \
          --text file://<filename> \
          --text-type text \
          --voice-id Kendra