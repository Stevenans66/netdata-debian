MAINTAINERCLEANFILES= $(srcdir)/Makefile.in

dist_noinst_DATA = \
	README.md \
	rhel/build-netdata-rpm.sh \
	$(NULL)

dist_noinst_SCRIPTS = \
	nc-backend.sh \
	$(NULL)

debian/changelog:
	echo "netdata ($(PACKAGE_VERSION)) UNRELEASED; urgency=medium" | \
		tr '_' '~' > $@
	echo "  * Latest release" >> $@
	echo " -- Netdata Team <>  `date -R`" >> $@
