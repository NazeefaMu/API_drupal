# Drupal API for employer dashboard

Display data fetched from drupal site

## Getting Started

### Prerequisites

- PHP 7
- MySQL

### Installing the module

- Upload "drupal_api" module to files
- Enable module in drupal site(Once enabled,table named api_configuration will be created
  in database)
- Set up the configuration data in "admin/config/development/drupal_api_settings"
  .The required data are as following:
   1. API key(Provide a strong key value)
   2. Node ID(The node ID to which the webforms related to jobs belong)
   3. CID (Content ID to check against the job offer ID)
   4. RID(Role ID of employers)
- RUN endpoints to fetch data by providing API key

### Reference document for API response format

Link : (https://docs.google.com/document/d/1KTwsZnVpz5cw3f2Et8FiKLoRcIOxzahkJ410s-OvAdE/edit)


## Authors
* **Nazeefa Musthafa** - *Initial work* [nazeefa98](https://github.com/nazeefa98/careerfirst-drupal-api)

* **Prageeth Peiris** - *Developer*

* **Akila Anuranga** - *Developer*



## Acknowledgments

* DARTX Pvt. Ltd. Made with ❤
