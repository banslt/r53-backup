# route53-backup

Backup recordsets of all your hosted zones into a s3 bucket.

# Usage:

- build sam app: ``sam build``

- deploy sam app: ``sam deploy -g``

- select your preferences in the prompt

- trigger the lambda ``aws lambda invoke --function-name <FUNCTION-NAME-HERE>``

- get your recordslists from the S3 bucket. 

*(sam cli can be installed from Pypi: `pip install aws-sam-cli` (Python >=3.6))*