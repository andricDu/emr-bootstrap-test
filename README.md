# emr-bootstrap-test
Test if you need S3 hosting for a bootstrap in AWS EMR


## Conclusion

Path to boostrap action must be using one of the following
  - `s3://`
  - `file://`
  
It is invalid to use `https://` or `http://`

Test was performed October 10th 2018.
