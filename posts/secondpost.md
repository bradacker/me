---
title: How to Start a Blog with Netlify CMS for Free
date: 2019-01-01T00:00:00.000Z
summary: Start a free blog that you can grow into the future.
tags:
  - Netlify
  - Github
---
Starting a blog is a great way to share your thoughts, ideas, and experiences with the world. And thanks to platforms like Netlify and Eleventy, it's never been easier to get your blog up and running – and the best part is, it won't cost you a cent!

First things first: what is Netlify and Eleventy, and why should you use them to start your blog?

Netlify is a cloud-based platform that makes it easy to build, deploy, and host websites and web applications. It's popular among developers because it offers a host of powerful features, including continuous deployment, automatic HTTPS, and a global CDN, all of which make it easy to deliver fast, reliable websites.

Eleventy is a static site generator that allows you to create websites and blogs using simple template languages like Markdown and Liquid. It's a great tool for bloggers because it lets you focus on creating content, rather than worrying about the underlying technology.

[JAMStack](https://jamstack.org/) websites and apps that deliver better performance, higher security, lower cost of scaling, and a better developer experience.

Why you need to choose Netlify over WordPress or any other option ([A List of Content Management Systems for JAMstack Sites](https://headlesscms.org/)).

Wordpress hosting can get expensive over time. I wanted a way to lower my cost and started to look for better options. I was aware of the security risks also even though my sites have only been hacked in once and nothing was done to them that I know of. 

Option one that I found was static sites for increased speed and security.

[A List of Static Site Generators for JAMstack Sites](https://www.staticgen.com/)

[Netlify templates](https://templates.netlify.com/) deploy in minutes.

This site is built with [Eleventy + Netlify CMS Boilerplate](https://templates.netlify.com/template/eleventy-netlify-boilerplate/). After trying many of the other Netlify Template options, I found this to be the best working and easiest to use. This is coming from a Github beginner and Wordpress CMS user.

So, how do you get started with Netlify and Eleventy?

1. Sign up for a free Netlify account. This will give you access to all the features you need to get your blog up and running, including continuous deployment, automatic HTTPS, and a global CDN.
2. Install Eleventy on your computer. Eleventy is built using Node.js, so you'll need to have that installed on your machine first. You can then install Eleventy using npm, the Node.js package manager:

   ```
   `npm install -g @11ty/eleventy`
   ```
3. Create a new Eleventy project. Once you have Eleventy installed, you can create a new project by running the following command:

   ```
   eleventy --create

   ```

This will create a new directory with the necessary files and directories to get your blog up and running.

4. Write your first blog post. Eleventy uses Markdown to write blog posts, so you'll need to create a new Markdown file in the `_posts` directory. You can then write your blog post using the Markdown syntax.
5. Deploy your blog to Netlify. Once you're happy with your blog, it's time to deploy it to Netlify. Simply connect your Netlify account to your Git repository (if you don't already have one, you can create one for free using GitHub or GitLab), and then push your code to your repository. Netlify will automatically build and deploy your blog, making it available to the world.

And that's it! You now have a fully-functional, free blog, thanks to Netlify and Eleventy. Happy blogging!