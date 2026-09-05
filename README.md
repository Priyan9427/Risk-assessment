
# EXPERIMENT 5
## NAME  : Priyan U
## REGNO : 212224040254

## ASSET-ORIENTED RISK ASSESSMENT OF STORAGE ASSETS IN AWS 


## Aim

To identify storage assets in **AWS S3**.


## Software / Cloud Services Required

- AWS Account
- Microsoft Azure Account
- Web Browser
- Internet Connection

### Cloud Services Used

| Cloud Platform | Storage Service |
|---|---|
| AWS | Amazon S3 |


## AWS S3 STORAGE ASSESSMENT

## Step 1: Login to AWS

1. Open the AWS Management Console.
2. Sign in using your AWS account.
3. Search for **S3**.
4. Select **Amazon S3**.


## Step 2: Select the S3 Bucket

1. Click **Buckets**.
2. Select the S3 bucket created in the previous experiment.
3. Record:
   - Bucket name
   - AWS Region
   - Number/type of objects
<img width="1797" height="772" alt="image" src="https://github.com/user-attachments/assets/f1a80ef7-9642-40b0-9b3b-b05067f820bc" />





## Step 3: Check Block Public Access

1. Open the S3 bucket.
2. Select **Permissions**.
3. Locate **Block public access (bucket settings)**.
4. Check **Block all public access**.

### Record

- **ON** → Secure configuration
- **OFF** → Potential public-access risk
<img width="1785" height="747" alt="image" src="https://github.com/user-attachments/assets/cd9e1c75-312a-4461-bd95-509a8d9d47e5" />








## Step 4: Check Bucket Versioning

1. Select the **Properties** tab.
2. Locate **Bucket Versioning**.
3. Record whether it is:
   - Enabled
   - Disabled

### Security Purpose

Versioning helps recover previous versions of objects after accidental deletion or modification.

<img width="1785" height="751" alt="image" src="https://github.com/user-attachments/assets/5dcd37d5-f057-4320-b51e-cc6a79580288" />





## Step 5: Check Default Encryption

1. Stay in the **Properties** tab.
2. Locate **Default encryption**.
3. Record the encryption type.

### Possible Configurations

- SSE-S3
- SSE-KMS
- DSSE-KMS

### Security Purpose

Encryption protects stored data from unauthorized disclosure.

<img width="1780" height="766" alt="image" src="https://github.com/user-attachments/assets/130041c6-bbd5-4004-95e4-d266d14fa1ca" />



## Step 6: Check Bucket Policy

1. Select **Permissions**.
2. Locate **Bucket policy**.
3. Check whether a bucket policy exists.

### Record

- Policy exists
- No policy

> **Note:** A missing bucket policy is not automatically a vulnerability. Access may be controlled through IAM and other AWS security mechanisms.

<img width="1778" height="740" alt="image" src="https://github.com/user-attachments/assets/56dbd2c2-6ba9-4b8a-aebc-93c074f6a5e8" />



## Step 7: Check Object Ownership and ACL

1. In **Permissions**, locate **Object Ownership**.
2. Record the current configuration.

A common secure configuration is:

**Bucket owner enforced**

This means:

- ACLs are disabled.
- Objects are owned by the bucket owner.
- Access is controlled using policies.
<img width="1223" height="510" alt="image" src="https://github.com/user-attachments/assets/618a8135-538d-4560-81a3-18da5ffcdf5d" />




## Step 8: Check Server Access Logging

1. Go to **Properties**.
2. Locate **Server access logging**.
3. Record whether it is:
   - Enabled
   - Disabled

### Security Purpose

Logging helps investigate suspicious or unauthorized access to the bucket.

<img width="1222" height="503" alt="image" src="https://github.com/user-attachments/assets/a5c4c12f-3277-4ce1-8894-74ed1f58a86e" />





## Result

AWS S3 security configurations were analyzed and potential risks were identified.



