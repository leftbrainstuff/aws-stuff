aws polly start-speech-synthesis-task \
          --engine standard \
          --language-code en-AU \
          --output-format mp3 \
          --output-s3-bucket-name ifal-ml-scratch \
          --output-s3-key-prefix audio-novel/igf-novel-chapter-one-to-three \
          --sample-rate 24000 \
          --text file://igf-novel-chapter-one-to-three.txt \
          --text-type text \
          --voice-id Kendra