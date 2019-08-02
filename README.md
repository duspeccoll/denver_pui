# University of Denver Libraries ArchivesSpace Public User Interface Customizations

What we've done:

1. Changed the stylesheets so that they abide by the DU style guide
2. Changed titles and labels of and around our site
3. Changed the layout of the Welcome page so that the search form is above the about text
4. Display an alert in the object viewer if an archival resource has restrictions associated with it
5. Google Analytics

## Note on Google Analytics implementation

This plugin calls on the 'google_analytics_key' configuration setting, which you will need to add yourself to `config/config.rb`. To do this, append the following to that file:

```
AppConfig[:google_analytics_key] = "YOUR KEY HERE"
```
