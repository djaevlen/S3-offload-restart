# S3 offload restart

This is how to restart S3 offload and clear the queue

Go to your database and inside ```wp_options```delete the following ```option_name containing:

```as3cf_assets_files_``` and ```wpos3_process-assets_batch_```

That should do it.
