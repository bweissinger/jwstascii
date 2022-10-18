# [www.jwstascii.com](jwstascii.com)
![cosmic_cliffs](/.doc_resources/cosmic_cliffs.png)

Behold! Images from mankind's largest optical space telescope rendered in breathtaking 200 column ascii art, updated daily.

## A Little Bit More...
This repo contains the site files for [jwstascii.com](jwstascii.com), a static site hosted from an S3 bucket and served through CloudFront. Updates are automated through an [AWS Lambda function](https://github.com/bweissinger/jwstascii-lambda-updater). The function scrapes the [webb telescope](https://webbtelescope.org) site daily for a new image to showcase.

## Infrastructure
![architecture_diagram](/.doc_resources/architecture.png)