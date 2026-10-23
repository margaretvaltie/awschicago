# AWS Chicago User Group Website

Static site for the AWS Chicago User Group, served at awschicago.com and chicagoaws.com.

## Hosting

AWS Amplify Hosting deploys the `main` branch automatically. Pull requests get Amplify preview URLs.

## How it works

- Plain HTML and CSS. No build step.
- The contact form posts to Formspree (form ID in `contact.html`). Recipients and spam settings live in the Formspree dashboard.
- Security headers are set in `customHttp.yml`, which Amplify reads on deploy.

## Making changes

Branch from `main` using `type/description` (for example `chore/update-links`), open a PR, and check the Amplify preview before merging.
