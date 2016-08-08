# my-keystone-demo

## generate config

```
chenyang@chenyang-pc:/tmp/xxdebug4/my-test-project$ yo keystone

Welcome to KeystoneJS.

? What is the name of your project? My Site
? Would you like to use Jade, Nunjucks, Twig or Handlebars for templates? [jade | nunjucks | twig | hbs] nunjucks
? Which CSS pre-processor would you like? [less | sass | stylus] less
? Would you like to include a Blog? Yes
? Would you like to include an Image Gallery? Yes
? Would you like to include a Contact Form? Yes
? What would you like to call the User model? User
? Enter an email address for the first Admin user: devin.chen@gmail.com
? Enter a password for the first Admin user:
 Please use a temporary password as it will be saved in plain text and change it after the first login. admin
? Would you like to include gulp or grunt? [gulp | grunt | none] grunt
? Would you like to create a new directory for your project? Yes
? ------------------------------------------------
    KeystoneJS integrates with Mandrill (from Mailchimp) for email sending.
    Would you like to include Email configuration in your project? Yes
? ------------------------------------------------
    Please enter your Mandrill API Key (optional).
    See http://keystonejs.com/docs/configuration/#services-mandrill for more info.
    
    You can skip this for now (we'll include a test key instead)
    
    Your Mandrill API Key: 
? ------------------------------------------------
    KeystoneJS integrates with Cloudinary for image upload, resizing and
    hosting. See http://keystonejs.com/docs/configuration/#services-cloudinary for more info.
    
    CloudinaryImage fields are used by the blog and gallery templates.
    
    You can skip this for now (we'll include demo account details)
    
    Please enter your Cloudinary URL: 
? ------------------------------------------------
    Finally, would you like to include extra code comments in
    your project? If you're new to Keystone, these may be helpful. Yes
```

## install

```
git clone https://github.com/xxd3vin/my-keystone-demo.git
cd my-keystone-demo
npm install
```

create `.env` config file

```
# password: admin
COOKIE_SECRET=c2698deaa99b4eb6a695a7428a59f541b05fb38631a7ec20bcaa02ff14343d43b2322554a93ef883b78d0e08ce0a9c0d8aa70536c1bce4cc396433eaa8ab97f2
CLOUDINARY_URL=cloudinary://333779167276662:_8jbSi9FB3sWYrfimcl8VKh34rI@keystone-demo
MANDRILL_API_KEY=NY8RRKyv1Bure9bdP8-TOQ
```
