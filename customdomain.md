# Custom Domain

In Sheetly, when you create a website, your domain will be in following format:

> site.sheetly.page/$GOOGLE_SHEET_ID$

That means, visitors can access to your website with that link. However, if you want to connect this link to your domain or any subdomain, follow the steps:

1. Buy a domain if you don't have
2. Upgrade your Sheetly account to [PRO](https://sheetly.page)
3. Edit your domains DNS account like the following configuration:

Add **A** record with **@** host value that points to **64.227.16.94**.
If you will have a multi language website, you can edit like following screenshot:

![Image](https://sheetly.s3.amazonaws.com/docs/Screenshot+from+2020-06-22+12-22-10.png)
(I added one root domain, and one for spanish version)

4. In your Google Sheet, go to **Settings** sheet and edit **B17** column with your domain
5. Publish your website
6. Visit your domain
7. Voila!

Your old visitors will be redirected to your new domain.

If you have any question, don't hesitate to e-mail me.
