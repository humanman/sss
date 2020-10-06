# sss

aws s3 cp .\* s3://mdco-bucket-of-power
aws s3 cp . s3://mdco-bucket-of-power --recursive

aws cloudfront create-distribution --origin-domain-name