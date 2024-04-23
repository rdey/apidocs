
# How to Use Our Widget

Thank you for choosing our widget! This guide will walk you through the process of integrating and using our widget with the provided HTML code. The widget allows you to embed an iframe displaying different types of content from the specified source. Follow these steps to get started:

## Step 1: Copy the HTML Code

First, copy the HTML code provided below. You can paste this code into your website or web application where you want the widget to appear. Note! You will receive `{YOUR_COMPANY_SLUG}` from us, and you'll need to insert it into the code.

```html
<div style="display: flex;
  flex-direction: column; width: 100%; min-height: 300px;">
    <iframe
      src="https://www.redeye.se/ir-iframe/{YOUR_COMPANY_SLUG}?style=light&type=research"
      style="border: none; height: 100%; width: 100%;"
      title="Iframe IR Redeye"
    />
</div>
```
Replace `{YOUR_COMPANY_SLUG}` with the parameter provided by us.

## Step 2: Paste the Code

Paste the copied code into the HTML source code of your website or web application. You can place the widget wherever you want it to appear. Make sure to maintain the structure and styles as provided in the code. Adjust the surrounding `div` height and width to fit your website layout.

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
          src="https://www.redeye.se/ir-iframe/{YOUR_COMPANY_SLUG}?style=light&type=research"
          style="border: none; height: 100%; width: 100%;"
          title="Iframe IR Redeye"
        />
    </div>

    <!-- More of your website content here -->
</body>
</html>
```

## Step 3: Customize the Widget and Choose Content Type

You can customize the widget by modifying the HTML and CSS properties as needed. Here are some customization options:

**Style**:
You can adjust the style to your website by choosing `light` or `dark` background to your widget. Default is `light`.

**Type**: 
You can choose between three different types of widgets depending on what type of content you want to highlight on your website. 
- `research` will show a list containing the 5 latest articles published by Redeye on your company. 
- `event` will show a video player containing the most recent Event Presentation, CEO Interview or Analyst Interview featuring your company.
- `landing` will show a smaller widget that highlights what sort of information about your company an investor can access through Redeye and provides direct links to said content.

The default (accessed by omitting `type` from the URL) is the depricated widget which resembles the new `research` type.

## Step 4: Test and Publish

After pasting the code and making any necessary customizations, save your changes and test your website or application to ensure that the widget is displayed correctly. If everything looks good, you can go ahead and publish your site or application with the widget integrated.

That's it! You've successfully integrated our widget into your website or application. If you have any questions or encounter any issues, please don't hesitate to reach out to us for assistance ([joel.karlsson@redeye.se](mailto:joel.karlsson@redeye.se)). We're here to help you make the most of our widget.
