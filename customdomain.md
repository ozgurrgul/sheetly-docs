# Custom Domain

In Sheetly, when you create a website, your domain will be in following format:

> site.sheetly.page/$GOOGLE_SHEET_ID$

That means, visitors can access to your website with that link. However, if you want to connect this link to your domain or any subdomain, follow the steps:

1. Buy a domain if you don't have
2. Upgrade your Sheetly account to [PRO](https://sheetly.page)
3. Edit your domains DNS account like the following configuration in your domain provider panel:

Add **A** record with **@** host value that points to **64.227.16.94**:

![Image](https://sheetly.s3.amazonaws.com/docs/Screenshot%2Bfrom%2B2020-06-22%2B12-22-10.png)

4. In your Google Sheet, go to **Settings** sheet and edit **B17** column with your domain
5. Publish your website
6. Visit your domain
7. Voila!

?> Your visitors will be redirected to your new domain if they visit your sheetly.page url.

---

!> **Important**: After configuring above steps, please shot me a DM in twitter @ozgurrgul or reach me through email (ozgurgul @ yandex com) with the following information so I can set up SSL certificate for you:

- Your domain
- Your sheet id
- Your email
