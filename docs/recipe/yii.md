<!-- DO NOT EDIT THIS FILE! -->
<!-- Instead edit recipe/yii.php -->
<!-- Then run bin/docgen -->

# yii

[Source](/recipe/yii.php)



* Require
  * [`recipe/common.php`](/docs/recipe/common.md)
* Config
  * [`shared_dirs`](#shared_dirs)
  * [`writable_dirs`](#writable_dirs)
* Tasks
  * [`deploy`](#deploy) — Deploy your project

## Config
### shared_dirs
[Source](/recipe/yii.php#L9)

* Overrides [`shared_dirs`](/docs/recipe/common.md#shared_dirs) from `recipe/common.php`

Yii shared dirs

### writable_dirs
[Source](/recipe/yii.php#L12)

* Overrides [`writable_dirs`](/docs/recipe/deploy/writable.md#writable_dirs) from `recipe/deploy/writable.php`

Yii writable dirs


## Tasks
### deploy
[Source](/recipe/yii.php#L18)

Main task

This task is group task which contains next tasks:
* [`deploy:prepare`](/docs/recipe/common.md#deployprepare)
* [`deploy:vendors`](/docs/recipe/deploy/vendors.md#deployvendors)
* [`deploy:publish`](/docs/recipe/common.md#deploypublish)


