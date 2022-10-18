# PhotographyPortfolio

## Description
This is a photography portfolio website where I display my photos to the world

## Sections
The website consists of 4 sections
- **Home**: This is a section consisting of a short welcome message, an image of myself and a contact button
- **About**: This section contains an image of me and a short description about myself
- **Gallery**: This section consists of a slideshow displaying multiple photos that users can scroll through
- **Collection**: The final section contains photos from my most recent photoshoot

## Hosting
The website is hosted using Amazon S3 and AWS CodePipeline. The following steps explain the process for hosting
1. Create a bucket on Amazon S3
2. Configure bucket settings to allow public access and static website hosting
3. Create a pipeline on AWS CodePipeline
4. Add GitHub as the source and create a new connection to the website repository
5. Deploy pipeline
