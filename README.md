## Overview
This composer project is used for testing the Drupal AI module.

## Quick start

1. **Enable DDEV**

   ```shell
   ddev start
   ```

2. **Install Composer**

   ```shell
   ddev composer install
   ```

3. **Install Standard install profile**

   ```shell
   ddev . drush si -y
   ```

2. **Enable the drupalai module**

   ```shell
   ddev . drush en -y drupalai
   ```

4. **Login to test**

   ```shell
   ddev . drush uli
   ```


**Read drupalai module documentation**

Please refer to the following instruction for configuration/usage:

https://github.com/drupalninja/drupalai/
