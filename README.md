# Cloud Resume Challenge

I am taking the following approach to put my resume on the cloud.

Challenge Website: https://cloudresumechallenge.dev

I am electing to use AWS as my platform.

## Initially

1. Make a static resume with bootstrap and inspiration from the web.
2. Manually put the website up on AWS S3 and version control this repo with GitHub.
3. Purchase a domain name.
4. Redirect Domain Name to S3 Static Website.

## Leveling UP

1. Setup Automatic Updates via GitHub Actions.
2. Setup and Configure AWS Route 53 and no longer do a domain name redirect.
3. Secure via SSL (HTTPS)
4. Make it so that a change in the website respository on GitHub automatically updates the S3 site.

## Beyond that.

Move toward using infrastructure as code solutions (IaC) via AWS CloudFront, establish that I can
persist data with a database, and create general robustness.

I would like to incorporate a PDF download option so that I can ultimately treat this resume as
my Authoritative Source of Truth (ASoT).  For example, I maintain my web resume, and if I were
to ever apply for a job I can download it and attach to an application.  I could also include
the website on said application as well.

