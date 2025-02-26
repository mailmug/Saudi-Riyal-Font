<p align="center"><a href="#logo"><img src="https://raw.githubusercontent.com/mailmug/saudi-riyal-font/main/img.png" width="830" alt="SAR currency symbol Font"></a></p>


# Saudi Arabian Riyal (SAR) Currency Symbol Font  

Saudi Arabian Riyal (SAR) currency symbol.   It includes OTF and SVG formats

## Font Name
Font Name is **Arshid**


## Usage
To use the font, install the OTF file on your system.

## Demo
**Demo:** https://demo.phpbolt.com/demo.html

## How to use in HTML?

### 1. Using @font-face (Recommended)
This method allows you to load the font from your server.

#### Step 1: Upload the Font Files
Make sure your Arshid.otf (or .woff, .woff2) is in your website directory, preferably in a folder like:

```bash
/fonts/Arshid.otf
```

#### Step 2: Add CSS
Include this in your CSS file or <style> tag:

```css
@font-face {
    font-family: 'Arshid';
    src: url('fonts/Arshid.otf') format('opentype');
    font-weight: normal;
    font-style: normal;
}

.sar{
    font-family: 'Arshid', sans-serif;
}
```

```html
<p><span style="font-family: 'Arshid';">$</span>100</p>

```

### 2. Using Google Drive / CDN (Alternative)
If you upload the font to GitHub or a CDN, you can reference it directly in CSS:

```css
@font-face {
    font-family: 'Arshid';
    src: url('https://your-web-link/Arshid.otf') format('opentype');
}
```
