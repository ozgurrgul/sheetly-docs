# Multi-language Websites

With Sheetly, you can create multi language websites easily only with your Google Sheets. In Google Sheets, there is a powerful function called GOOGLETRANSLATE(). Below examples based on _GOOGLETRANSLATE_ and _IMPORTRANGE_ functions.

In the following example, our english website holds all the texts and I translated spanish version automatically. Converting it to spanish took only 10 minutes. If you want, you can even create 50 languages translation of your website easily, this would boost your SEO.

- [Startup Website (English)](https://my-company.xyz)
- [Startup Website (Spanish)](https://es.my-company.xyz)

For example, I only used the following formula for the cell that I want to translate to spanish:

?> =GOOGLETRANSLATE(IMPORTRANGE("1iJbJDrnrJj_CgKfGnL78MHOpjjKKFIO1GKgNfT6fUVU","Team!B4"), "en", "es")

And I connected them to _my-company.xyz_ (english) and _es.my-company.xyz_ (spanish) domains.

## Steps to create a multi-language website

For this example, we will create english & spanish versions of our website.

1. Create a Sheetly website, preferably fill cells in **english** and that will be the base for all translations for your websites
2. After you feel like it's finished, make a copy of that Sheet (_File > Make a copy_)
3. Open new copied sheet
4. Make it public (File > Share, then change to **Anyone with the link**)
5. If you want to use it with your custom domain, be sure you checked the steps in [custom domain](/customdomain) page (optional)
6. Update **Settings:B17** cell with your custom domain (optional)
7. For the cells you want to translate, paste this formula and edit it for each cell:

_=GOOGLETRANSLATE(IMPORTRANGE("**your_base_english_sheet_id**","**Team**!**B4**"), "**en**", "**es**")_

Explanation: This formula fetches the **B4** cell value from our **Team** sheet in the english sheet, then converts it from **english** to **spanish**. Like a magic! :)

?> **your_base_english_sheet_id** is the document id of your sheet in the step 1

If you want to add more language, repeat the steps 2-7.
