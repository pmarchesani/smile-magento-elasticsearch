Global information :
====================

This module provides a ElasticSearch implementation for Magento.

Module : ElasticSearch

Contact: Aurelien FOUCRET <aurelien.foucret@smile.fr>


Basic installation :
====================

- First you will need to install a version of ElasticSearch > 0.90.x and ensure it is running (port 9200 by default)

- This module can run on both Magento CE and Magento EE edition. 

  **If you are using EE edition, you should take care about installing this module disables Enterprise_Search module.**

- You can configure the search engine into ***System -> Configuration -> Catalog -> Catalog Search***

- The suite is shipped with a tracker, which is intended to collect data that can be used for :

  -- search engine enhancement
  -- analytics
  -- rum data collection
  
  The module is called Smile_Tracker and you can disabled it if you don't want to rely on these features.