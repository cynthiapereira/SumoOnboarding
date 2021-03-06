# SumoOnboarding

This repo contains the codes for the Get Involved pages of [Mozilla Support](https://support.mozilla.org), which aim to provide a better experience for new contributors on how to start contributing to our Knowledge Base, L10n, Support Forum and Social Support.

## Getting Started

This is a widget that is meant to display custom content based on the custom page that you display. You need a Lithium instance and access to Custom components for this freemarker widget to work. 

With a copy the project, fill in the html with the steps and the names of the custom pages. 

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

1. Lithium Instance
1. Access to Studio
1. Create custom pages and remember their names
1. Knowledge of Freemarker and basic HTML and CSS

## Running the tests

There are no automated tests, publishing and testing your links are the best way to check to make sure that the page detected shows the correct content. 

Test the widget to make sure: 

1. You do not have duplicated content. Look for comments between if statements and look for html comments that might be comenting out freemarker
2. Test your html seperate from the freemarker 
3. Make sure that CSS is not the same name as style from the Lithium Skinn

## Deployment

You will need 3 custom pages
And you will need to create 3 custom components

In this repo there are three html files with the names and mark up in each component. The each can be added to a custom page by their name on the quilt you have selected for your custom page. 

### How to add a Custom Component

To Do

### How to edit a Custom Component

1. Go to the page name
1. Look up the component name
1. Click on components
1. Edit the component name that you found from the page name
1. Click save
1. Preview 
1. Change accordingly 
1. If you need to publish (note the time you made the change for queued studio version)

### How to create conditionais

You can use `if`, `elseif` and `else` directives to conditionally skip a section of the template.

**Example:**
```
<#if expression>

<#else>

</#if>
```

### How to create a Custom Page

To Do

### How to add icons

If you want to use one of the icons in the Font Awesome version 4.3, you can just call it out by name by adding the class `lia-fa` and appending the `lia-` prefix to the desired Font Awesome icon.

**Example:**
```
<i class="lia-fa lia-fa-pencil-square-o lia-fa-4x" aria-hidden="true"></i>

```

### How to add or edit SASS/CSS 

To Do

## Built With

* [Freemarker](https://freemarker.org/) - The web framework used
* [Lithium](https://www.lithium.com/) - Software host
* [Font Awesome](http://fontawesome.io/icons/) - Icons

## Contributing

Please request a pull request or open an issue with a description of what you wantt to work on. Since this is unter MIT Lisence is comes as it is.

## Versioning

We use git for versioning as well as the queued version numbers built into Lithium. 

## Authors

* **Cynthia Pereira** - *Initial work* - [CynthiaPereira](https://github.com/cynthiapereira)
* **Rachel McGuigan** - *Initial work* - [Turtleloveshoes](https://github.com/turtleloveshoes)


See also the list of [contributors](https://github.com/turltleloveshoes/SumoOnboarding/contributors) who participated in this project.

## License

This project is licensed under the MIT License 

## Acknowledgments

* Cynthia for the html and vision for a new ui design 
* Inspiration - A new platform for SUMO and an opportunity to update documentation and welcome new users into the community. 
* etc