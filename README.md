Install the prismic.io command line interface (CLI):

```npm install -g prismic-cli```

Launch this command. You'll get a local copy of this code and a preconfigured prismic.io content repository to populate the landing pages.

```prismic theme https://github.com/lamenath/landing-page-theme```

Change the prismic.io API endpoint in ```prismic-config.js``` (set it to https://{your-repo}.prismic.io/api)

Go to the prismic.io repository you've just created with the CLI

Populate content for a page, **give it the ```sample-page``` uid** , publish

In your terminal, run the app:

```nodemon```

Head to http://localhost:3000/

Configuring the Preview: 

- In your prismic.io backend, head to `/settings/previews/`
- Add a new site, give it any name and set the site URL to http://localhost:3000/preview

Once the preview is configured, you can hit the preview button from the backend from any page you'll create. You'll be redirected to the right page (e.g., http://localhost:3000/[uid]) to preview the front-end in your browser.
