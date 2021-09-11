Contentful Gatsby Starter Blog

Create a Gatsby blog powered by Contentful.

The index page of the starter blog

Static sites are scalable, secure and have very little required maintenance. They come with a drawback though. Not everybody feels good editing files, building a project and uploading it somewhere. This is where Contentful comes into play.

With Contentful and Gatsby you can connect your favorite static site generator with an API that provides an easy to use interface for people writing content and automate the publishing using services like Travis CI or Netlify.
Features

    Simple content model and structure. Easy to adjust to your needs.
    Use the synchronization feature of our Delivery API.
    Responsive/adaptive images via gatsby-image and our Images API.

Getting started

See our official Contentful getting started guide.
Get the source code and install dependencies.

$ git clone https://github.com/contentful/starter-gatsby-blog.git
$ npm install

Or use the Gatsby CLI.

$ gatsby new contentful-starter-blog https://github.com/contentful/starter-gatsby-blog/

Set up of the needed content model and create a configuration file

This project comes with a Contentful setup command npm run setup.

This command will ask you for a space ID, and access tokens for the Contentful Management and Delivery API and then import the needed content model into the space you define and write a config file (./.contentful.json).

npm run setup automates that for you but if you want to do it yourself rename .contentful.json.sample to .contentful.json and add your configuration in this file.
Crucial Commands
npm run dev

Run the project locally with live reload in development mode.
npm run build

Run a production build into ./public. The result is ready to be put on any static hosting you prefer.
npm run serve

Spin up a production-ready server with your blog. Don't forget to build your page beforehand.
Deployment

See the official Contentful getting started guide.
Contribution

Feel free to open pull requests to fix bugs. If you want to add features, please have a look at the original version. It is always open to contributions and pull requests.

You can learn more about how Contentful userland is organized by visiting our about repository.
