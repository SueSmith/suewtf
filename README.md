# My social website! 🌎🪩🎡

> ⚠️ **Glitch project hosting shuts down on 8th July 2025 so you won't be able to remix this project anymore – you are welcome to use the source code if you'd like to deploy it somewhere else!**

![project in glitch](https://github.com/user-attachments/assets/c10ed5b0-7f08-4a8b-ac04-b90cacadb90b)

This is a website you can remix to make your own. Open the __Preview__ pane at the bottom of the Glitch editor to see your changes appear live. On the left you'll find the files that make up your site, including HTML, JavaScript, and CSS. You can upload images in __Assets__. Go ahead and edit your remix! 🪄

You can use this site with your own domain and for social media platforms:

* <a href="https://dev.to/glitch/verify-your-bluesky-or-mastodon-account-on-your-own-domain-with-a-free-website-1jfn" target="_blank">**Follow the tutorial to verify your accounts on Bluesky and Mastodon!**</a>

## What's in this project?

← `README.md`: That's this file, where you can tell people what your cool website does and how you built it.

← `index.html`: This is the main web page for your site. The HTML defines the structure and content of the page using _elements_. You'll see references in the HTML to the JS and CSS files. Try clicking the image in the center of the page!

← `style.css`: CSS files add styling rules to your content. The CSS applies styles to the elements in your HTML page. The style rules also make the image move when you click it.

← `script.js`: If you're feeling fancy you can add interactivity to your site with JavaScript. The code in the JavaScript file runs when the page loads.

← `package.json`: NPM packages your website uses during development.

← `vite.config.js`: Your site uses Vite to build and serve it to users.

Open each file and check out the comments (in gray) for more info.

## Use this site to verify your social media accounts

### Bluesky

In the Bluesky app, navigate to **Settings** > **Account** > **Handle** and click **I have my own domain**.

* You can use your `your-project.glitch.me` address if you like, or a domain you own that you're pointing at this site. Enter the domain.
* Choose **No DNS panel** and copy the `did` text.
* In your Glitch project, add a file named `.well-known/atproto-did` and paste the value in there.

Back in Blueksy, verify the domain and update to use it as your handle.

### Mastodon

For Mastodon, open `index.html` and update the link near the end of the page to point to your own Mastodon profile.

* In your Mastodon account, edit your profile, adding a link to this website.
  * You can use the `your-domain.glitch.me` address, or a domain you're pointing at this website.
  
Mastodon will verify your domain and highlight it in your profile.

![Glitch](https://cdn.glitch.com/a9975ea6-8949-4bab-addb-8a95021dc2da%2FLogo_Color.svg?v=1602781328576)

## You built this with Glitch!

[Glitch](https://glitch.com) is a friendly community where millions of people come together to build web apps and websites.

- Need more help? [Check out our Help Center](https://help.glitch.com/) for answers to any common questions.
- Ready to make it official? [Become a paid Glitch member](https://glitch.com/pricing) to boost your app with private sharing, more storage and memory, domains and more.
