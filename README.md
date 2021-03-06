<!--- The following README.md sample file was adapted from https://gist.github.com/PurpleBooth/109311bb0361f32d87a2#file-readme-template-md by Gabriella Mosquera for academic use --->

# Assignment 2 - Advanced Web Services

### SiteURL: <https://foodcore.netlify.com/>

This prototype was created to provide a seamless experience, as such I opted not to include three seperate routes, instead I included all three pages accessible at one route. In future iterations there would be routing and authentication for specific pages. This was a design choice, as I wanted the pages to be connected and share data without using a site store such as redux, or make database queries at this time.

- _Date Created_: 31 Jan 2020
- _Last Modification Date_: 03 Feb 2020

## Authors

- [Sam Irvine](sam.irvine@dal.ca) - _(Developer)_

## Getting Started

See deployment for notes on how to deploy the project on a live system.

### Prerequisites

To have a local copy of this lab / assingnment / project up and running on your local machine, you will first need to install the following software / libraries / plug-ins

```
GatsbyJS

```

See the following section for detailed step-by-step instructions on how to install this software / libraries / plug-ins

### Installing

A step by step series of examples that tell you how to get a development env running

```
1. npm install -g gatsby-cli in terminal

2. git clone the repo to your local machine (using https)

3. run 'npm i' in project folder to ensure node modules are up to date

4. gatsby develop in the new project folder

5. The project will be available on localhost:8000

```

End with an example of getting some data out of the system or using it for a little demo. You may also include a quick example of what the marker should see if the installation of all required software / libraries / plug-ins was successful.

### Intended Features

This is the expected functionality of each feature

```
1. The list should intitially allow you to add up to 6 items, then requiring you to register. The checks and hearts will also require registration, item info was not implemented for this assignment, so it will prompy email verification.

2. The Pricing plans should prompt the login/Register, with the plan the user selected.

3. The Login/Registration was made minimal, and I will expand on it in future iterations. At this time it only does basic form validation (email check, password not blank).

```

## Deployment

The simplest way to deploy this site is to use Netlify. Netlify works out of the box with Gatsby therefore all you must do is point it to the project repository.

## Built With

<!--- Provide a list of the frameworks used to build this application, your list should include the name of the framework used, the url where the framework is available for download and what the framework was used for, see the example below --->

- [Gatsby](https://github.com/gatsbyjs/gatsby) - The web framework used
- [React](https://github.com/facebook/react) - Gatsby sites are built using React
- [React Spring](https://github.com/react-spring/react-spring) - Used for animations

## Sources Used

All of the code was created by myself, or generated by the Gatsby default starter template.

- [Gatsby](https://github.com/gatsbyjs/gatsby-starter-default) - The Starter Template

I referenced the React Spring renderProps Documentation when creating the animations

- [React Spring](https://www.react-spring.io/docs/props/) - The animation framework documentation
