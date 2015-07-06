#Drupal Boilerplate#
-

Drupal boilerplate is not a module. Instead it just serves as a directory structure for
starting a new drupal site. The idea behind Drupal boilerplate came from working on so many
different sites which each follow their own development practice, directory structure,
deployment guidelines, etc...

Drupal boilerplate tries to simplify starting a new site by having the most common
directory structures and files already included and set up.

##Getting started##
You can start by [downloading](https://github.com/TallerWebSolutions/drupal-boilerplate/zipball/master)
this project. Once you download it you will find that every folder contains a readme.md file.
This readme.md file has been extensively documented to explain what belongs
in that specific directory.

Here's a breakdown for what each directory/file is used for. If you want to know more please
read the readme inside the specific directory.

* [drush](https://github.com/TallerWebSolutions/drupal-boilerplate/tree/kraftwagen/drush)
 * Contains project specific drush commands, aliases, and configurations.
* [results](https://github.com/TallerWebSolutions/drupal-boilerplate/tree/kraftwagen/results)
 * This directory is just used to export test results to. A good example of this
   is when running drush test-run with the --xml option. You can export the xml
   to this directory for parsing by external tools.
* [scripts](https://github.com/TallerWebSolutions/drupal-boilerplate/tree/kraftwagen/scripts)
 * A directory for project-specific scripts.
* [tests](https://github.com/TallerWebSolutions/drupal-boilerplate/tree/kraftwagen/tests)
 * A directory for external tests. This is great for non drupal specific tests
 such as selenium, qunit, casperjs or cucumber.
* [databases](https://github.com/TallerWebSolutions/drupal-boilerplate/blob/kraftwagen/databases)
 * The databases directory is used to place dumps from the persistant storages like MySQL,
 MongoDB and others, used for the initial boot in new environments.
* [configs](https://github.com/TallerWebSolutions/drupal-boilerplate/blob/kraftwagen/configs)
 * The configs directory is used to place configurations of other softwares like Apache Solr,
 Redis, MongoDB and others.
* [.gitignore](https://github.com/TallerWebSolutions/drupal-boilerplate/blob/kraftwagen/.gitignore)
 * Contains the a list of the most common excluded files.
* [Kraftwagenrc](https://github.com/TallerWebSolutions/drupal-boilerplate/blob/kraftwagen/kraftwagenrc.php)
 * Contains configurations to use Kraftwagen, by default only overwrite the dir build to docroot in order to provide easier integration with Acquia.

Built by Robots&trade;
