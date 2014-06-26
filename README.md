plugin-publish-s3
=================

Datawrapper plugins that publishes charts to an Amazon S3 bucket.

To configure:
1. Set up an S3 bucket with the correct CORS permissions. Several examples are available here: [http://docs.aws.amazon.com/AmazonS3/latest/dev/cors.html]
1. Add your bucket name, access key and secret key to the main Datawrapper configuration file. 
1. Clone this repository into _<datawrapper-dir>_/plugins/publish-s3
1. Install the plugin: `php scripts/plugin.php install publish-s3
