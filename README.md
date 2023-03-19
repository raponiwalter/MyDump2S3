# MyDump2S3
mysqldump to S3

Dumps mysql to local disk, gzip it and send it to S3 through awscli consolle.

usage: ./mydump2s3 -n "productiondb stagingdb" -b "mybucket-name"

Use mydump2s3 -h to see full options list
