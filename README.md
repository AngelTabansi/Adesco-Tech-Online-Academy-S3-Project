# Adesco Tech Online Academy — AWS S3 Project

**Project by:** Angel

## Project Overview

This project demonstrates the use of Amazon Simple Storage Service (Amazon S3) for company document storage, file versioning, storage lifecycle management, and static website hosting.

The project involved creating a private S3 bucket for company documents and a separate S3 bucket for hosting the Adesco Tech Online Academy website.

## Project Objectives

- Create an Amazon S3 bucket for company documents.
- Upload three company documents.
- Enable bucket versioning to help protect files.
- Keep the company documents bucket private.
- Configure a lifecycle policy to help optimize storage costs.
- Create a separate S3 bucket for static website hosting.
- Upload the `index.html` website file.
- Configure website access permissions and test the website in a browser.

## AWS Services Used

| AWS Service or Feature | Purpose |
|---|---|
| Amazon S3 | Stores company documents and website files. |
| S3 Bucket Versioning | Maintains versions of objects to help protect against accidental changes or deletions. |
| S3 Block Public Access | Helps prevent public access to the private company documents bucket. |
| S3 Lifecycle Configuration | Automates storage transitions or other configured lifecycle actions. |
| S3 Static Website Hosting | Hosts the static academy website. |
| S3 Bucket Policy | Controls access to objects in the website bucket. |

## Project Implementation

### Task 1: Create an S3 Bucket

Created the company documents bucket:

`adesco-company-documents-angel`

### Task 2: Upload Company Documents

Uploaded three company documents into the S3 bucket.

### Task 3: Enable Versioning

Enabled bucket versioning to help protect company files and preserve object versions.

### Task 4: Configure Bucket Privacy

Kept Block Public Access enabled on the company documents bucket to help ensure that the documents remain private.

### Task 5: Configure a Lifecycle Policy

Configured an S3 lifecycle policy to automate storage management and help optimize storage costs.

### Task 6: Host a Static Website

Created a separate S3 bucket for the academy website and uploaded the `index.html` file.

### Task 7: Configure Website Access

Enabled static website hosting and configured the website bucket policy to permit public reading of the website content.

**Security distinction:** The company documents bucket remains private, while the website bucket is configured for public read access to support website hosting.

### Task 8: Test the Website

Opened the website in a browser and verified that the Adesco Tech Online Academy page was displayed.

The website includes a home page, an About section, course information, and contact information.

## Challenges Encountered

- Understanding S3 bucket creation and configuration.
- Managing file uploads and versioning.
- Keeping company documents private.
- Configuring lifecycle policies.
- Setting up static website hosting.
- Configuring website bucket permissions.
- Testing the website in a browser.

## Skills Demonstrated

- Amazon S3 bucket management.
- Cloud object storage.
- File versioning and data protection.
- Storage lifecycle management.
- AWS access control and bucket policies.
- Static website hosting.
- Basic cloud security practices.
- Website deployment and testing.

## Project Documentation

The `ANGEL_AWS_S3.docx` file in this repository contains the assignment report and screenshots documenting the implementation steps.

## Conclusion

This project provided practical experience with Amazon S3 storage, versioning, lifecycle management, access permissions, and static website hosting.

**Project status:** Completed as a hands-on AWS training assignment.
