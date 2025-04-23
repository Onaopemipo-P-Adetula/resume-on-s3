# resume-on-s3
Host a resume on AWS S3 with public access
#Architecture Diagram
![Architecture diagram](https://github.com/user-attachments/assets/ef2f8d86-272a-49c9-8e88-8b6b9361cd6a)

# Host a Resume on AWS S3

This project demonstrates how to host a publicly accessible resume (CV) using AWS Simple Storage Service (S3). It's a quick and effective way to showcase basic cloud skills while also giving recruiters direct access to your CV.

---

## Features
- Public static file hosting on AWS S3
- Simple IAM and bucket policy configuration
- Public link to access CV

---

## Tools Used
- AWS S3
- AWS IAM

---

## Steps to Reproduce

### 1. Prepare Your CV
- Convert your resume to PDF or HTML format.
- Rename it to something like `resume.pdf` or `index.html`.

---

### 2. Create an S3 Bucket
1. Go to [AWS S3 Console](https://s3.console.aws.amazon.com/s3/home).
2. Click “Create bucket”.
3. Name it something unique (e.g., `your-fullname-resume`).
4. Uncheck **Block all public access** (required for public access).
5. Under Object Ownership, select ACLs enabled.
6. Acknowledge the warning and create the bucket.

---

### 3. Upload Your Resume
1. Open your bucket.
2. Click “Upload”.
3. Choose your `resume.pdf` or `index.html`.
4. Under Permissions, check Grant public read access.
5. Upload the file
---

### 4. Make It Public
1. Select the uploaded file.
2. Copy the Object URL.
3. Paste the URL into a new browser tab to verify public access.
---




