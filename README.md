# My online ScatchPad

#### Download from specific S3 bucket/directory and grep for pattern + 100 characters

`$  aws s3 sync s3://secret-bucket/N2ECustomerSync/Failure/2016-02-23/ 2016-02-23/`

`$  grep -r --no-filename -E -o '."response": .{0,100}' 2016-02-23`
