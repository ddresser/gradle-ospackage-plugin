v0.8 - 2011-08-04
=================
  * add defines of RPM_ARCH, RPM_OS, RPM_PACKAGE_NAME, RPM_PACKAGE_VERSION,
    and RPM_PACKAGE_RELEASE to scripts to be consistent with rpmbuild

v0.7 - 2011-06-28
=================
  * add support for a utilities script that automatically gets included in
    any pre/post/preun/postun scripts

v0.6 - 2011-06-27
=================
  * add specification of required dependencies

v0.5 - 2011-06-10
=================
  * add default for sourcePackage because Yum's createrepo assumes your rpm
    is a source package without it
  * default packageName to the project.name

v0.4 - 2011-06-06
=================
  * initial Maven Central release