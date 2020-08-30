# Old version of Drupal 7 ready to install.

Used by me in my old projects (D7), kept here only for study and maintenance purposes.

No more Drupal 7 projects are development by me from the publication of Drupal 8.

Supported until November 2022. Use this version for sites already running Drupal 7.

- Update to 7.72
- Spanish core locale file included.

# Main branch.

Drupal 7 clean, ready to install, does not contain any customization.

Remenber to select Spanish locale or English.

<div align="center">
  <img src="capture.JPG"  width="400" height="auto">
</div>

# Development Branch.

Work branch, contains Drupal 7 already installed, with a basic configuration and customized by me.

- Includes the Database, to import it.
- Username: admin
- Password: drupal
- Only administrator allow to create accounts.
- Core disabled modules:
  + Color
  + Overlay
  + Comment
  + Help
- Includes settings.php with the usual configurations to avoid the most common errors.
- Remenber to change, mail@mail.com, user and password.

# Custom modules added by me.

Development Branch include my personal selection of modules, used by default in my projects.

Only "Navbar" and "Backup and Migrate" modules are enable by defauld in this branch.

- Administration
  + Navbar
- Fields type
  + Email
  + Link
  + Entity reference
- News Chanels (Import data)
  + Feeds
- Spam Control
  + Captcha
  + reCaptcha
  + Honeypot
- Analytics
  + Google Analytics
- Development
  + Database Optimization
  + Devel
- EntityForms
  + EntityForms
- Time/Date
  + Date
  + Week day field
- Input Filters
  + Pathologic
- User interface
  + jQuery Update
  + Wysiwyg
- CHAOS TOOL SUITE
  + CHAOS Tools
- Sitemap
  + XML Sitemap
- Menu
  + TB Mega Menu
- Multilingual
  + Localization client
  + Localization update
- Multimedia
  + File Entity
  + Media
  + PDF Preview
  + SVG Embed
- Plus/Others
  + Automatic Nodetitles
  + Backup and Migrate
  + Block Attributes
  + Empty Front Page
  + Entity API
  + EU Cookie Compilance
  + Exclude node title
  + Font Awesome
  + Node clone
  + Password toggle
  + Pathauto
  + RobotsTxt
  + Simple Google Maps
  + Sitemap
  + Site Verification
  + Special Menu Items
  + Token
  + Ultimate Cron
- Panels
  + Panels
  + Panels BootStrap Layout
- Rules
  + Rules
- SECURITY
  + Copy Prevention
  + Flood Unblock
  + Login Security
  + Paranoia (Plus Paranoia Sanitize)
  + No request new password
  + Security Review
- SEO
  + Metatag 
- Display Suite
  + Display Suite
- Views
  + Views
  + Views BootStrap
  + Views Conditional
  + Views Field View
  + Views PDF Display

# Libraries Modules and libraries added by module dependencies.
They can be found in /sites/all/libraries, all updated to the latest versions with the exception of those that need a module in a specific version.

- Libraries
  + Backbone JavaScript library
  + Underscore JavaScript library
  + Modernizr custom build
  + tcpdf (6.0.0.22)
  + fpdi (1.6.2)
  + Tinymce