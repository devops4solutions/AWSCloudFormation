### Create a S3 bucket
- Upload a teamplate
- Create a changeset
- Verify the changes
- Execute the changes
- Validate S3 bucket is created

# Update S3 bucket
 - update new file `s3_update.yaml`
 - Add a new property AccessControl
 - Update the stack
 - Preview the changes
 - This update doesn't require any replacement

# Update S3 bucket name
 - This update requies a replacement
 - It will delete the old bucket and create the new bucket
 - You can only delete empty buckets. Deletion fails for buckets that have contents.

# Delete the stack
- For accidental deletion, you can enable the termination protection
- When you delete the stack all the resources will automatically get deleted




 