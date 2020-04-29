Bulma Start Template
------------------------------------------------------------
Clone the repository and:
- npm install
- yarn install
- yarn start
------------------------------------------------------------
Use s3_website to deploy the website to S3
- gem install s3_website
- s3_website cfg create
- Customize the settings in file s3_website.yml
- s3_website cfg apply to create bucket
- s3_website push to deploy the Dist folder to S3 bucket
- website is live!