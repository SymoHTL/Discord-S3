# Discord-S3 API Roadmap

This document outlines the API endpoints to be implemented for S3 compatibility.

## Service Operations
- [ ] `ListBuckets` (GET Service)

## Bucket Operations
- [ ] `CreateBucket` (PUT Bucket)
- [ ] `DeleteBucket` (DELETE Bucket)
- [ ] `ListObjects` / `ListObjectsV2` (GET Bucket)
- [ ] `GetBucketLocation` (GET Bucket?location)
- [ ] `GetBucketAcl` (GET Bucket?acl)
- [ ] `PutBucketAcl` (PUT Bucket?acl)
- [ ] `HeadBucket` (HEAD Bucket)
- [ ] `ListMultipartUploads` (GET Bucket?uploads)

## Object Operations
- [ ] `GetObject` (GET Object)
- [ ] `PutObject` (PUT Object)
- [ ] `DeleteObject` (DELETE Object)
- [ ] `HeadObject` (HEAD Object)
- [ ] `CopyObject` (PUT Object?copy) - Destination object
- [ ] `GetObjectAcl` (GET Object?acl)
- [ ] `PutObjectAcl` (PUT Object?acl)
- [ ] `DeleteMultipleObjects` (POST Bucket?delete)

## Multipart Upload Operations
- [ ] `CreateMultipartUpload` (POST Object?uploads)
- [ ] `UploadPart` (PUT Object?partNumber=PartNumber&uploadId=UploadId)
- [ ] `UploadPartCopy` (PUT Object?partNumber=PartNumber&uploadId=UploadId&x-amz-copy-source=Source)
- [ ] `CompleteMultipartUpload` (POST Object?uploadId=UploadId)
- [ ] `AbortMultipartUpload` (DELETE Object?uploadId=UploadId)
- [ ] `ListParts` (GET Object?uploadId=UploadId)