# ditchyourpoolguy.com

Landing page for Blue Pro — hosted on S3 + CloudFront, deployed via GitHub Actions on push to `main`.

## Deployment

Push to `main` → GitHub Actions syncs `index.html` to S3 and invalidates CloudFront.

## Required GitHub Secrets

- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`
