colony361
=========

Mini site for the Colony 361 (2013-09) event.

### Local Build
```
jekyll build --config _config_local.yml
jekyll serve --watch --config _config_local.yml
```

### AWS S3 Sync
```
cd colony361/
aws --profile default --region eu-west-1 s3 cp static s3://afrobanana/colony361/static --recursive --exclude static/css/src/*
```

