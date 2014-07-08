plugin-publish-s3
=================

Datawrapper plugins that publishes charts to an Amazon S3 bucket. 

To configure:

1. Set up an S3 bucket with the correct CORS permissions. Several examples are available here: http://docs.aws.amazon.com/AmazonS3/latest/dev/cors.html
2. Add your bucket name, access key and secret key to the main Datawrapper configuration file. 
3. Clone this repository into _<datawrapper-dir>_/plugins/publish-s3
4. Install the plugin: `php scripts/plugin.php install publish-s3

Available configuration settings:
```
plugins:
  publish-s3:
    accesskey: <access key>
    secretkey: <secret key>
    bucket: <bucket name>
    alias: <URL to use instead of the default Amazon S3 bucket URL>
    endpoint: <custom endpoint, in case the typical S3 endpoint doesn't work>
```
