<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.gatsbyjs.org">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/Gatsby-Monogram.svg" width="60" />
  </a>
</p>

# Nero the Shepherd

> A photo blog for my Shepherd, Nero. Powered by Gatsby and WordPress.

[![Netlify Status](https://api.netlify.com/api/v1/badges/e14bab10-7c74-4339-bd0d-41cd1c3bc49f/deploy-status)](https://app.netlify.com/sites/nero-the-shepherd/deploys)

![Henry the Pug](nero-the-shepherd-com.jpg)

I built this site for my dog Nero. Originally built in 2016, for my other dog Henry using WordPress and the Instagram API, as a photo blog to store some photos and watch how much he grew. This time around I wanted something different. So I built it using WordPress as a headless CMS for the back-end and used Gatsby for the front-end. It's blazing fast. I kept the site design pretty muc hthe same, It's still powered by the Instagram API, just swapped the tech stack.

Posts get created by a cron job and script on the server. The cron job check Instagram twice a day. If there's a new post it will create a WordPress post and attach the media to it. The post creation triggers a web hook that then triggers a new site build on Gatsby Cloud.