This package provides debian packages for simplified installation of ODN.

Content of solr directory is as-is copy of solr configuration directory with schema.xml from CKAN.

TODO:
- replace hostname in configuration files
- package UnifiedViews
- establish package repository

Usage: apt-get install odn-simple

Till the package repository will be established use this

~~~bash
# dpkg -i odn-ckan-shared_2.2.1-1_amd64.deb  odn-simple_0.9-1_amd64.deb  odn-solr_0.9-1_amd64.deb
... some dependency errors
# apt-get install -f -y
