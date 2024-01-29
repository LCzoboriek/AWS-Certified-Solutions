## S3

By default of created buckets are private.

You can controll access using policies or ACL

You can log who accesses the bucket and how in a different bucket

## Encryption

- Encryption in Transit is achieved by SSl/TLS
- Encryption at Rest (Server Side) is achieved by amazon encrypting the object for you using
  1. S3 Managed Keys - SSE-S3
  2. AWS Key Management Service - SSE-KMS
  3. Server Side encryption with Customer Keys - SSE-C
- You can also encrypt it yourself client side

You encrypt individual objects, or at a bucket level.
