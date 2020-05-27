# lambda-thumbnailer
https://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html

AWS Lambda thumbnailer with support for GIFs and PDFs (first page/frame)

Saves the thumbnails to SOURCE_BUCKET/thumbnails/SOURCE_KEY.png

Can easily be modified to save thumbnails as a different format, bucket, etc

Adds some metadata, and enables public-read for the thumbnail. 
