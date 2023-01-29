# Jump QRs

This repository shows how to create and use dynamic QR codes. This a code that you can scan, but which will land on a different page based on the configuration in this repository at the time of scan.

In other words, if you change your website or have a different mood today, you don't need to go reprint all your QR codes.

## How to use this demo

Visit the site at https://fulldecent.github.io/jump-qrs/ and scan any of the QR codes.

## How to update the QR code destination

Edit the files in [_jumps/](_jumps/) or add new files there in the format of those files.

## How to steal this

Copy this repository using the FORK button at top. This allows you to make any changes you like without requiring me to accept your changes. You have free reign. In your repository click SETTINGS and then turn on GitHub Pages (this will tell you what URL your site is accessible at). You can also host it this way for free on your own domain name.

Also you can add branding and other creative elements to the exeperience.

You can also run this on your own computer as follows:

1. Install [Homebrew](https://brew.sh/).

2. Using terminal run:

   ```sh
   bundle install
   bundle exec jekyll serve
   ```

3. See the URL that prints out (for me it is http://localhost:4000) and access that in your browser.
