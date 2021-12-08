# Drupal ZSH Plugin

Mainly inspired from [Artisan ZSH plugin](https://github.com/jessarcher/zsh-artisan) by Jess Archer

* new function `droot` to go from anywhere within a drupal project to the root directory.
* `drush` function auto-completion.
* common `drush` tasks aliases (cache/config).

## Requirement

* [zsh](https://www.zsh.org/)
* [oh-my-zsh](https://ohmyz.sh/)
* [drush](https://www.drush.org/)
* [drush-launcher](https://github.com/drush-ops/drush-launcher) or drush installed in your global $PATH with another method :)

## Installation

### Manual

```
git clone https://github.com/yhaefliger/zsh-drupal.git ~/.oh-my-zsh/custom/plugins/drupal
```

Add `drupal` in the plugin directive of your `.zshrc` file

## Aliases

* `dcr`: drush cache:rebuild
* `dcc`: drush cache:clear
* `dcex`: drush config:export
* `dcim`: drush config:import
* `dcget`: drush config:get
* `dcset`: drush config:set
* `dcedit`: drush config:edit
