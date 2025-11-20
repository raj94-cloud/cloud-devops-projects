# Static Website Hosting on AWS S3 + CloudFront

## Architecture
- Upload website files to S3 bucket
- Enable Static Website Hosting
- Create CloudFront distribution with S3 as origin
- Optional: Add Route53 domain

## Steps
1. Create S3 bucket → Enable static hosting
2. Upload files → Set bucket policy to public OR use OAI
3. Create CloudFront distribution → Point to S3
4. Invalidate cache on updates
