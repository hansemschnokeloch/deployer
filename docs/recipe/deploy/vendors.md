<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit recipe/deploy/vendors.php -->
<!-- Then run bin/docgen -->

# vendors

[Source](/recipe/deploy/vendors.php)



* Config
  * [`composer_action`](#composer_action)
  * [`composer_options`](#composer_options)
  * [`composer_version`](#composer_version)
  * [`composer_channel`](#composer_channel)
* Tasks
  * [`deploy:vendors`](#deployvendors) — Installing vendors

## Config
### composer_action
[Source](/recipe/deploy/vendors.php#L5)



### composer_options
[Source](/recipe/deploy/vendors.php#L7)



### composer_version
[Source](/recipe/deploy/vendors.php#L18)

Can be used to choose what composer version to install.
Valid values are any that are [listed here](https://getcomposer.org/download/).

For example:
```php
    set('composer_version', '10.10.15')
```

### composer_channel
[Source](/recipe/deploy/vendors.php#L23)

Set this variable to stable, snapshot, preview, 1 or 2 to select which Composer channel to use


## Tasks
### deploy:vendors
[Source](/recipe/deploy/vendors.php#L54)



