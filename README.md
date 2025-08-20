
#  Hosting a Static Website on Amazon S3 

This guide documents the steps I followed to host a static website on **Amazon S3**
All steps include screenshots for easier understanding.

---

## 📌 Prerequisites
- An **AWS Account** with access to S3.
- Screenshots are stored in the `/aws-s3-static-website` folder of this repository.

---

## 1 Create an S3 Bucket
- Go to the **S3 Console** and click **Create bucket**.
- Give your bucket a unique name and select a region.  
![Create Bucket](/image1.jpeg)

---
## 2 Enable Static Website Hosting
- In the bucket settings, go to **Properties** → **Static website hosting**.
- Enable hosting and set **index.html** as the default page.  
![Enable Hosting](aws-s3-static-website/image2.jpeg)


---
## 3 Upload Website Files
- Open your newly created bucket.
- Upload your static website files (HTML).  
![Upload Files](aws-s3-static-website/image4.jpeg)

---
## 4 Make Files Public
- Go to the **Permissions** tab.
- Adjust the bucket policy to allow public access to your website.  
![Set Permissions](aws-s3-static-website/image5.jpeg)


---
## 5 Test using S3 website endpoint
-copy the static hosting URL in a new tab
![Testing](aws-s3-static-website/image6.jpeg)


---
## Conclusion
You now have:
- A static website hosted on **Amazon S3**.

---

### 📖 Resources
- [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)

---

*Author: Ryan Luhongo
*Created on: August 2025
