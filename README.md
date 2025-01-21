# Static Website on AWS S3

Welcome to my static website hosted on AWS S3! 

## Website URL

[Visit the Website](http://my-static-website-490r.s3-website-us-east-1.amazonaws.com)

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Folder Structure](#folder-structure)
- [Technologies Used](#technologies-used)
- [Deployment on AWS S3](#deployment-on-aws-s3)

---

## Overview

This repository contains a simple static website built with HTML and CSS. It showcases a small image gallery and a welcome message. The site is designed to be lightweight, fast, and easily hosted on AWS S3.

---

## Features

- **Responsive Layout**: Adjusts to different screen sizes using basic CSS.
- **Image Gallery**: Displays three images (papaya, pineapple, raspberry) with a slight staggered offset and a hover effect.
- **Minimalistic Design**: Uses basic CSS for a clean and simple user experience.

---

## Folder Structure

```
.
├── index.html
└── images/
    ├── papaya.jpeg
    ├── pineapple.jpeg
    └── raspberry.jpeg
```

- **index.html**: Main entry point for the static website.
- **images/**: Directory containing images used in the gallery.

> Note: In your actual GitHub repository, be sure to include any image files in the correct location (e.g., `images/` or another directory you’ve referenced in `index.html`).

---

## Technologies Used

- **HTML5**: Structure of the webpage.
- **CSS3**: Styling and layout of elements.
- **AWS S3**: Hosting the static website.

---

## Deployment on AWS S3

Below is a simplified overview of how you can deploy this static site on AWS S3:

1. **Create an S3 Bucket**  
   - Log in to your AWS console.  
   - Create a new S3 bucket (e.g., `my-static-website-490r`).

2. **Configure the Bucket for Static Website Hosting**  
   - In the bucket settings, enable **Static website hosting**.  
   - Specify the **Index document** (e.g., `index.html`).

3. **Upload Your Files**  
   - Upload your `index.html` and any image files into the bucket.  
   - Make sure your files have **public read access** (or use an appropriate bucket policy/CORS configuration).

4. **Access Your Site**  
   - Use the given **Endpoint URL** (similar to `http://my-static-website-490r.s3-website-us-east-1.amazonaws.com`) to access your site.

For detailed instructions, refer to the [AWS S3 Documentation](https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteHosting.html).

