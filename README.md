# Huawei P40 Set up
My Huawei P10 is running out of storage, time to get a new phone.
I bought Huawei P40.

My main reason is that I don't want to get lock in to Google. I want to only use apps that can run on my old P10 and new P40 (with Google GMS ban on).

## User Experience Log
### 2 days
After 2 days of using, I am not blocked in my work or my daily life.

The User Experience (UX) on P40 is quite pleasant.

Its camera takes stunning picture. I took a picture of my garden in pitch darkness without flash, it came up with a stunning clear picture! 

### 8 days - 1 week
A colleague noted Google Maps icon on my phone. It must have being copied from my old phone. I tried it, it works but can not login. I was worried when I get Google Maps Timeline email from Google that Google record my travel in such a great details. With this Huawei phone, I am happy that Google has one less avenuie to track me.

I just noticed that when I turn on the phone from dark screen to screen lighted up, it recognizes my face and automatically unlock it.

After one week of using, I am not deprived of any functionalities.

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

## Chinese Keyboard: Microsoft Swiftkey

I use Microsoft Swiftkey for Chinese character entry and continual English word entry.

Continual English word entry is setup after Phone Clone.

For Chinese character entry, I only need to:
- Open Microsoft Swiftkey
- Add Chinese Simplified


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

- Go to https://github.com/settings/security, Authenticator App - Edit
- Use DUO MOBILE to scan the barcode appeared
- Enter the code, Enable
DONE


## Email

I use couple of gmail accounts. I was expecting I was not able to use them. I was pleasantly surprised that it is really easy to connect to gmail.
- Open Email (I believe this is Huawei Email app)
- Add account -> select Gmail -> enter my credential
- I did the same for all my other gmail accounts

## Calendar

Calendar seems to automatically sync all the connected gmail accounts.


## Slack

My company use slack. Open the app, sign in with Google works fine.

## Banking app

### ANZ GoMoney

Tried on first day, not able to login. On second day, it suddenly worked.
- Open ANZ GoMoney
- Enter user-id and password -> enter verification code (sent through SMS)

## 2 degree app

2 degree is a New Zealand mobile telecommunications company. It gives 1 hour free data connection daily via its custom **Data Clock** app. When the app starts up, a pop up saying "Data Clock won't run without Google Play service ...". Beside the warning message, the app runs fine and I can consume free data connection.

