# 01 - Create a SharePoint Department Permission Group

## Goal

Create a SharePoint permission group for a department, so I can give access to a whole department at once instead of adding people one by one.

## Environment
- Microsoft 365 through my school account
- Site: SharePoint Practice Lab (team site from [**01 - Create a Team Site**](../01-site-setup/01-create-team-site.md))
- I don't have admin rights on my school tenant, so I can't use the **Microsoft 365 admin center**  or **Microsoft Entra admin center** to create security groups. I made a **SharePoint group** at the site level instead. See [**If I had admin access**](#if-i-had-admin-access) for how this is normally done at work

---

## Steps

### 1. Sign in to Microsoft 365

Go to [https://m365.cloud.microsoft](https://m365.cloud.microsoft) and sign in.

<img width="933" height="659" alt="1" src="https://github.com/user-attachments/assets/cd64d7d4-acee-4657-986f-0c6afe1b9a57" />

### 2. Open SharePoint

Click the app launcher (the 9 dots, top left) and select **SharePoint**.

<img width="917" height="557" alt="2" src="https://github.com/user-attachments/assets/4705d4a8-994b-4468-894f-4ec067e0f3ce" />

<img width="958" height="740" alt="3" src="https://github.com/user-attachments/assets/59468a17-a7c7-4202-b41a-a6c81ed3026b" />

### 3. Open Site permissions

Open the site, click the **gear (Settings)** and select **Site permissions**.

<img width="1062" height="724" alt="4" src="https://github.com/user-attachments/assets/bfd30abc-6ecc-4bba-ab62-b5bb76bfbd5a" />

### 4. Go to Advanced permissions settings

The Site permissions panel shows the three default groups:

<img width="803" height="502" alt="5" src="https://github.com/user-attachments/assets/f11b57ab-f820-4b9b-b5be-d7a280242fd5" />

| Group | Access |
|---|---|
| **Site owners** | Full control |
| **Site members** | Edit |
| **Site visitors** | Read |

At the bottom, click **Advanced permissions settings**.

<img width="958" height="587" alt="6" src="https://github.com/user-attachments/assets/423c9868-de88-4249-a277-1f1bbe2ae819" />

### 5. Create the group

Click **Create Group** and fill it out:

<img width="1067" height="656" alt="7" src="https://github.com/user-attachments/assets/29a5696f-8e51-4d68-b32d-0a1bc32b1a8a" />

<img width="926" height="421" alt="8" src="https://github.com/user-attachments/assets/fa2abce4-403f-4aaa-8571-2847b3d0bdd8" />

### 6. Leave the permission levels unchecked

Under **Give Group Permission to this Site**, I left every box **unchecked** and clicked **Create**.

<img width="851" height="347" alt="9" src="https://github.com/user-attachments/assets/f6742a9a-491c-4821-969e-7b1765ea5966" />

Checking a box here gives the group that access across the **whole site**. I left them unchecked so the group starts with no access, and I give access separately later.

### 7. Add members

In the group, click **New → Add users**. Search for the person and hover over their name to make sure it's the right email. Add a message and click **Share**.

<img width="1042" height="601" alt="10" src="https://github.com/user-attachments/assets/0c5d8c36-26a0-498d-8202-f7f292bbb165" />















