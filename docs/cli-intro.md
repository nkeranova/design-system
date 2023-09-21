<head><link rel="stylesheet" type="text/css" href="media/cli-styles.css"></head>

<div class="hero-image">
  <div class="hero-text">
    <span>Axway CLI Style Guide</span>
  </div>
</div>

Axway CLIs should provide a clear user experience, targeted primarily for human readability and usability, which delights the user, while at the same time supporting advanced users. As the number of CLIs grows in the company, some discrepancies start to appear. The CLI Style Guide attempt to provide a set of recommendations for designing delightful and consistent CLIs. 
Input and output should be consistent across commands to allow the user to easily learn how to interact with new commands.

## Principles

* Strive for consistency across platforms
* Strive for consistency across commands
* CLIs are often part of an overall process, so it should be easy to pipe data in, and pipe data out
* Explicit should always override implicit
* Config files override default values
* Environment variables should override config values
* Command-line flags should override default, config and environment variables

