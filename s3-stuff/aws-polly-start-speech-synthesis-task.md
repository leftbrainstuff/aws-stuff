aws polly start-speech-synthesis-task \
          --engine standard \
          --language-code en-AU \
          --output-format mp3 \
          --output-s3-bucket-name <s3_bucket_name \
          --output-s3-key-prefix audio-novel/igf-novel-chapter-one-to-three \
          --sample-rate 24000 \
          --text file://<filename> \
          --text-type text \
          --voice-id Kendra