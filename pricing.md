# Pricing Sheet

<b>Pricing</b> sheet contains the data for pricing block. This block is used to show price of your business to visitors. You can add pricing tiers so visitors can compare and choose the best price for them. You can also integrate Stripe and redirect users to Stripe checkout process.

![Image](https://sheetly.s3.amazonaws.com/docs/pricing.png)

Configs to edit:

### title

Title

### description

A few words of description

### hide this block?

Should this block be hidden or not

### background color

Background color of this block

### text color

Text color like #444444 or #FF0000

### card background color

Card background color

### card text color

Card text color

### items

Items to sell. If you activate Stripe, visitors will be able to buy your item you sell

- Tier: Name of this tier like FREE, Premium or Starter etc
- Price: Price such as \$9.99 or £181.99
- Cycle: Write a cycle like mo, year, unlimited etc or keep empty
- Features: Write this tier's features by seperating them with <b>;</b>
- Button Text: Button text
- Button Link: Links should start with '/' if it's in your site, or you can also use 'http://' format. If you activate Stripe, you can keep empty
- Promote Tier: If you promote tier, there will be small "HOT" text at the corner of the item
- Stripe Activated?: If you enable Stripe, when button clicked, they will be redirect to Stripe Checkout screen
- Stripe Plan Id: Stripe plan or price id
- Mode: One time=payment. Recurring=subscription. You must choose one of them accordingly your pricing settings in Stripe
- Stripe Success URL: URL to redirect after a successful purchase
- Stripe Cancel URL: URL to redirect after a cancelled purchase
