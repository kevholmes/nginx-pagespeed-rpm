Nginx + Pagespeed .spec 
==============================================

Building the RPM
----------------

spectool -R -g nginx.spec

rpmbuild -ba nginx.spec

Updating to Newer Version of Nginx or Pagespeed
-----------------------------------------------

Update nps_version and Version in the SPECS/nginx.spec file.
