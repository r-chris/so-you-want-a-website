# So, you want a website?

Well, you've come to the right place. If you want to build your own website, but don't know where to start, there are a few things you should know.

## Domain Name

This is the web-address where your website can be found (e.g. r-chris.github.io). There are a number of freely available options, but if you are interested in `myname.com` / `myname.org` / `myname.info` you will generally have to register this address with a service provider and pay them a monthly fee.

## Website Hosting

This is where your website will be stored. You need space on a computer that is connected to the internet (also known as a server). You place your webpages onto this computer (just as you would with your regular documents) and then allow people from the internet to access these files.

### Self-Hosting from your home

Potentially, this could be your own computer in your home. If you have a somewhat *decent* internet connection (read: decent **upload** speed) and you only expect limited traffic to your webpage, you could host your own website on your own computer. In fact, Mac OS X ships with a build-in option to share a specific website folder with a single click.

As you can expect, this computer now has to be turned on 24h/day, because you expect your website to be available online 24h/day: it can never go to sleep! If you have a laptop, this probably isn't the solution you are looking for. The internet connection (your router) also has to stay online 24h/day. If anyone unplugs the router or you loose electricity (etc) your website will be offline. Maybe that's ok, but it's not something you expect to happen today. Lastly, your computer also has to be properly secured from potential attacks, because as soon as you open access to your computer, it becomes a target. I am not trying to scare you - you just need to know.

### Third-party Hosting

The obvious alternative is to host your website somewhere else. Imagine you have a Dropbox (or Google Drive, etc) folder that contains the files for your websites. In this case Dropbox uploads and stores these files somewhere for you (on their servers) and you can access them any time you want, right?

Ok, so Dropbox and Google Drive are free up to a specific amount and you would now think - great - let's just store the files there. Unfortunately, these services are not designed to host your websites. That is, because hosting a website is more than just sharing a folder with a few files and it's simply not their business model.

**Alright, so where then?**

## Github

Well, github for example allows you to create basic webpages for your projects, organizations or you as a user. There are even a number of default layouts you can choose from and you can assign an address in this form: r-chris.github.io
You can get started here: https://pages.github.com/

The basic approach is to:
 * Creata a new repository (name it how you would like to name the website: e.g. r-chris.github.io)
 * Navigate to the repository settings (not the github settings)
 * Click on `Launch automatic page generator`
 * Chose your template and enter your text, then publish it

The great thing is that you can now download, edit and replace the source code to your auto generated webpage with anything you like and therefore easily host any webpage through github this way. They also make it very easy for you to assign a custom URL if you prefer that over (r-chris.github.io) and have support to host `jekyll` blogs.

## Google Sites

You can also use a google service to do something similar, but it feels a bit outdated to be honest.

## A rented server

This is the more traditional approach. Often the service provider that you can register web-addresses with will also be able to host a website for you (for an additional fee). There may be more or less sensible storage and data transfer limitations connected to these offers that allow you to transfer X GB/month between the online storage you just rented and the users that come to visit your site. The (dis-)advantage of this is that you have to be somewhat comfortable with creating and uploading your own website as well as configuring the options

## Amazon Web Services (AWS)

This is the technically most demanding option that offers absolut control over the webpage and allows you to scale your webpage to millions of users per day. If done right, this is a lot cheaper than the previous renting option, because it comes with free usage quotas for the first year and follows the basic pay-by-use principle. There may very well be tutorials out there to setup your own website through AWS, but I can not recommend this for anyone who wants something quick and easy. If you are a bit more serious about this and feel comfortable learning about web services, you could start with this (official) video: https://www.youtube.com/watch?v=E78VKAPwmDM

## Profile Pages

If all that you are after is a profile of yourself, consider one of the social sites such as LinkedIn or ResearchGate. They generally allow you to create a fairly short url to share with anyone and those are trusted places where people know what to expect.

