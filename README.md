# Huawei P40 Set up
My Huawei P10 is running out of storage, time to get a new phone.
I bought Huawei P40.

My main reason is that I don't want to get lock in to Google. I want to only use apps that can run on my old P10 and new P40 (with Google GMS ban on).

## Huawei Phone Clone
After initiate setup, start Huawei Phone Clone at both P10 and P40.

3 apps are identified as not transferrable due to size.
- Baidu
- KanTV
- WeChat

I can ignore Baidu and KanTV as there is no data and I can re-install.

After Huawei Phone Clone, following apps are identified as not working:
- AT Park - an Auckland Parking application
- Authenticator
- Microsoft SwiftKey

Additionally, tried:
- Authy - not working
- ANZ gomoney - not working

## WeChat

Tried to use Phone Clone to transfer WeChat alone, the message says it needs 4.3 GB of space.
- I removed a number of apps and picture

Then, Phone Clone successfully transferred.

## 2FA: Use DUO Mobile to replace Authy

I use Authy for 2FA on AWS and github.

### AWS
On https://aws.amazon.com/iam/features/mfa/, DUO Mobile can used used and it seems to works on P10.
- Remove Authy by
  - Login to AWS
  - My Security Credentials
  - MFA Manage ->
  - MFA Manage -> Add, scan, enter first code, then second code.
  DONE
  
### github






