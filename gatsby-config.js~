module.exports = {
  siteMetadata: {
    title: `Melwy - blog`,
    name: `Melwy`,
    siteUrl: `https://melwy.com/blog`,
    description: `Blog - AI & data science for precision medicine and drug discovery`,
    hero: {
      heading: `Blog - AI & data science for precision medicine and drug discovery`,
      maxWidth: 652,
    },
    social: [
      {
        name: `twitter`,
        url: `https://twitter.com/mostafabenh`,
      },
      {
        name: `youtube`,
        url: `https://youtu.be/7ACNiebz0ko`,
      },
      {
        name: `linkedin`,
        url: `https://www.linkedin.com/in/mostapha-benhenda/`,
      },
      {
        name: `github`,
        url: `https://github.com/mostafachatillon`,
      },
        {
        name: `medium`,
        url: `https://medium.com/the-ai-lab`,
      },
    ],
  },
  plugins: [
    {
      resolve: "@narative/gatsby-theme-novela",
      options: {
        contentPosts: "content/posts",
        contentAuthors: "content/authors",
        basePath: "blog",
        sources: {
          local: true,
          contentful: false
        },
      },
    },
    {
      resolve: `gatsby-plugin-manifest`,
      options: {
        name: `Novela by Narative`,
        short_name: `Novela`,
        start_url: `/`,
        background_color: `#fff`,
        theme_color: `#fff`,
        display: `standalone`,
        icon: `src/assets/favicon.png`,
      },
    },
    {
      resolve: `gatsby-plugin-google-analytics`,
      options: {
        trackingId: "UA-118232427-3",
      },
    },
  ],
};
