# Drupal API for employer dashboard

Display data fetched from drupal site

## Getting Started

### Prerequisites

- PHP 7
- MySQL

## Installing the configuration page

- Install config_pages module using the following link.
 Link: (https://ftp.drupal.org/files/projects/config_pages-7.x-1.9.tar.gz)
- After module installed, navigate to "admin/structure/config_pages/types" and click on "Add config page".
- Enter config page title and mount point, for example "admin/config/mysettings" and menu item type.
- Choose context if you need (if for example you want to have different settings for different languages) and save config page.
- Go to "https://drupal8.local/admin/structure/config_pages/types" and find your config page there,
  add following fields.
  1. API KEY (machine name: field_portal_api_key)
  2. Node ID (machine name: field_portal_node_id)
  3. CID (machine name: field_portal_cid)
- The configuration page will appear on the list of configurations to view,insert needed
 values.

### Installing the module

- Upload "drupal_api" module to files
- Enable module in drupal site
- RUN endpoints to fetch data

## Authors
* **Nazeefa Musthafa** - *Initial work* [nazeefa98](https://github.com/nazeefa98/careerfirst-drupal-api)

* **Prageeth Peiris** - *Developer*

* **Akila Anuranga** - *Developer*



## Acknowledgments

* DARTX Pvt. Ltd. Made with ❤
