# docker-gatsbyjs
Gatsby starter project using Docker.

To install run

```
script/install
```

This will install GatsbyJS in your project. 

To run the development server:

```
docker-compose up -d app
```

# Interacting with the Gatsby app

During development, if you need to interact with npm, node or the Gatsby
CLI, you will run commands against the docker contianer.

For instance, if you need to run `npm install --save
some-gatsby-package` you will need to run this command against the
container:

```
docker-compose run --rm app npm install --save some-gatsby-package
```

```
docker-compose run --rm app [your command here]
```


# gatsby-starter-default

For an overview of the project structure please refer to the [Gatsby documentation - Building with Components](https://www.gatsbyjs.org/docs/building-with-components/)

Install this starter (assuming Gatsby is installed) by running from your CLI:
```
gatsby new gatsby-example-site
```

