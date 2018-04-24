#**CiviCRM banking extension**


- Development Status: stable
- Used for: Interface to configure and implement communication with bank. Implements handling of bank accounts for contacts, as well as handling of bank files (and individual bank payements extracted from the files). Bank files can be imported, payments matched to CiviCRM entities, and the resulting data exported. Specific handlers for all of these actions are provided through plugins, some of which are shipped with the core banking extension, while some more complex ones are provided in separate extensions.
- CMS Compatibility: 4.6, 4.7, 5
- Git URL: [click me]("https://github.com/systopia/CiviBanking")
- Fully Qualified Name: org.project60.banking
- Author: Systopia.


#**CiviBanking**

CiviCRM banking extension

Implements handling of bank accounts for contacts, as well as handling of bank files (and individual bank payements extracted from the files). Bank files can be imported, payments matched to CiviCRM entities, and the resulting data exported. Specific handlers for all of these actions are provided through plugins, some of which are shipped with the core banking extension, while some more complex ones are provided in separate extensions.


##**Documentation**

You can find the (preliminary) documentation in the [[**Project Wiki**]](https://github.com/Project60/org.project60.banking/wiki)


##**Development Installation**

Clone Repository and link the 'extension' folder of the CiviBanking project into you CiviCRM extensions folder, e.g. like this:

```> cd ~/Documents/mamp_root/drupal/sites/default/files/extensions/
> ln -s ~/Documents/workspace/CiviBanking/extension CiviBanking```

