
# How to Use Our Widget

Thank you for choosing our widget! This guide will walk you through the process of integrating and using our widget with the provided HTML code. The widget allows you to embed an iframe displaying content from the specified source. Follow these steps to get started:

## Step 1: Copy the HTML Code

First, copy the HTML code provided below. You can paste this code into your website or web application where you want the widget to appear. Note! You will receive `{YOUR_COMPANY_SLUG}` from us, and you'll need to insert it into the code.

```html
<div style="display: flex;
  flex-direction: column; width: 100%; min-height: 300px;">
    <iframe
      src="https://www.redeye.se/ir-iframe/{YOUR_COMPANY_SLUG}?style=light&size=large"
      style="border: none; height: 100%; width: 100%;"
      title="Iframe Example"
    />
</div>
```
Replace `{YOUR_COMPANY_SLUG}` with the parameter provided by us.

## Step 2: Paste the Code

Paste the copied code into the HTML source code of your website or web application. You can place the widget wherever you want it to appear. Make sure to maintain the structure and styles as provided in the code.

```html
<!DOCTYPE html>
<html>
<head>
    <!-- Your head content here -->
</head>
<body>
    <!-- Your other website content here -->

    <!-- Paste the widget code here -->
    <div style="display: flex;
      flex-direction: column; width: 100%; min-height: 300px;">
        <iframe
          src="https://www.redeye.se/ir-iframe/{YOUR_COMPANY_SLUG}?style=light&size=large"
          style="border: none; height: 100%; width: 100%;"
          title="Iframe Example"
        />
    </div>

    <!-- More of your website content here -->
</body>
</html>
```

## Step 3: Customize the Widget (Optional)

You can customize the widget by modifying the HTML and CSS properties as needed. Here are some customization options:

- **Style**: You can adjust the style to your website by choosing `light` or `dark` background to your widget. Default is `light`.
- **Size**: You can adjust the size with options `small` or `large`. Default is `large`.

## Step 4: Test and Publish

After pasting the code and making any necessary customizations, save your changes and test your website or application to ensure that the widget is displayed correctly. If everything looks good, you can go ahead and publish your site or application with the widget integrated.

That's it! You've successfully integrated our widget into your website or application. If you have any questions or encounter any issues, please don't hesitate to reach out to us for assistance ([louise.zetterlund@redeye.se](mailto:louise.zetterlund@redeye.se)). We're here to help you make the most of our widget.
