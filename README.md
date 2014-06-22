XML (NSOA)
==========

DESCRIPTION
-----------

A customized syntax file for aiding in the styling of Advanced Settings files in an NSOA SRP configuration.

This was created mainly for use in [Sublime Text](http://www.sublimetext.com) or [TextMate](http://macromates.com/), but can likely also be used in [Notepad++](http://notepad-plus-plus.org/) with some massaging.

AUTHORS
-------

Ryan Morrissey - [ryancmorrissey.com](http://ryancmorrissey.com)

LICENSE
-------

See [LICENSE.md](LICENSE.md)

INSTALLATION
------------

For _Sublime Text_, you can install directly from the git repo, or manually download the `XML (NSOA).tmlanguage` file from the repo and add it to your `User` folder.

```bash
# use this for Sublime Text on Mac/OSX
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User
git clone https://rmorrissey23@bitbucket.org/rmorrissey23/xml-srp.git XML-SRP

```

For _TextMate_, download the `XML (NSOA).tmlanguage` file from the repo and drag it into _TextMate_ to install.

Instructions for _Notepad++_ will hopefully be added soon, as a separate file type needs to be created for _NPP_.

DOCUMENTATION
-------------

You can run a test to ensure the syntax files are highlighting properly using the `advanced_mappings.nsoa.xml` file in the `/tests` directory.

#### Viewed as Plain Text - Tomorrow Night Color Scheme

![advanced_mappings.txt.png](https://bitbucket.org/rmorrissey23/xml-srp/raw/master/img/advanced_mappings.txt.png)

#### Viewed as XML (NSOA) - Tomorrow Night Color Scheme
![advanced_mappings.nsoa.xml.png](https://bitbucket.org/rmorrissey23/xml-srp/raw/master/img/advanced_mappings.nsoa.xml.png)
