# Boostrap v4 for Contact Form 7
My first and possibly the least advanced plugin for WordPress<br />
Contact Form 7 is a work of Takayuki Miyoshi
* [Find it on WordPress Respository](https://wordpress.org/plugins/contact-form-7/)

## What is this wonderful and amazing plugin do?
Changes default WordPress Contact Form 7 styles to Bootstrap v.4-alpha styles (wow!)

## You do not need to install this plugin!
(Just add these lines to your style.css file)
```css
.wpcf7 label {display: block;width: 100%;}
.wpcf7 input, .wpcf7 select, .wpcf7 textarea {display: block;width: 100%;padding: 0.5rem 0.75rem;font-size: 1rem;line-height: 1.25;color: #464a4c;background-color: #fff;background-image: none;-webkit-background-clip: padding-box;background-clip: padding-box;border: 1px solid rgba(0, 0, 0, 0.15);border-radius: 0.25rem;-webkit-transition: border-color ease-in-out 0.15s, -webkit-box-shadow ease-in-out 0.15s;transition: border-color ease-in-out 0.15s, -webkit-box-shadow ease-in-out 0.15s;-o-transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s;transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s;transition: border-color ease-in-out 0.15s, box-shadow ease-in-out 0.15s, -webkit-box-shadow ease-in-out 0.15s;}
.wpcf7 textarea::-ms-expand, .wpcf7 input::-ms-expand {background-color: transparent;border: 0;}
.wpcf7 select:focus, .wpcf7 textarea:focus, .wpcf7 input:focus {color: #464a4c;background-color: #fff;border-color: #5cb3fd;outline: none;}
.wpcf7 textarea::-webkit-input-placeholder, .wpcf7 input::-webkit-input-placeholder {color: #636c72;opacity: 1;}
.wpcf7 textarea::-moz-placeholder, .wpcf7 input::-moz-placeholder {color: #636c72;opacity: 1;}
.wpcf7 textarea:-ms-input-placeholder, .wpcf7 input:-ms-input-placeholder {color: #636c72;opacity: 1;}
.wpcf7 textarea::placeholder, .wpcf7 input::placeholder {color: #636c72;opacity: 1;}
.wpcf7 textarea:disabled, .wpcf7 textarea[readonly], .wpcf7 input:disabled, .wpcf7 input[readonly] {background-color: #eceeef;opacity: 1;}
.wpcf7 textarea:disabled, .wpcf7 input:disabled {cursor: not-allowed;}
select.wpcf7 textarea:not([size]):not([multiple]), select.wpcf7 input:not([size]):not([multiple]) {height: calc(2.25rem + 2px);}
select.wpcf7 textarea:focus::-ms-value, select.wpcf7 input:focus::-ms-value {color: #464a4c;background-color: #fff;}
.wpcf7 input[type="submit"] {cursor: pointer !important;margin-top: 0.5rem;display: inline-block;font-weight: normal;line-height: 1.25;text-align: center;white-space: nowrap;vertical-align: middle;display: block;width: 100%;-webkit-user-select: none;-moz-user-select: none;-ms-user-select: none;user-select: none;border: 1px solid transparent;padding: 0.5rem 1rem;font-size: 1rem;border-radius: 0.25rem;-webkit-transition: all 0.2s ease-in-out;-o-transition: all 0.2s ease-in-out;transition: all 0.2s ease-in-out;color: #292b2c;background-color: #fff;border-color: #ccc;}
.wpcf7 input[type="submit"]:focus, .wpcf7 input[type="submit"]:hover {text-decoration: none;}
.wpcf7 input[type="submit"]:focus, .wpcf7 input[type="submit"].focus {outline: 0;-webkit-box-shadow: 0 0 0 2px rgba(2, 117, 216, 0.25);box-shadow: 0 0 0 2px rgba(2, 117, 216, 0.25);}
.wpcf7 input[type="submit"].disabled, .wpcf7 input[type="submit"]:disabled {cursor: not-allowed;opacity: .65;}
.wpcf7 input[type="submit"]:active, .wpcf7 input[type="submit"].active {background-image: none;}
.wpcf7 input[type="checkbox"]{position: absolute;-webkit-box-sizing: border-box;box-sizing: border-box;padding: 0;}
```
