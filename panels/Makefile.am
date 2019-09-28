NULL =

enabled_panels = \
	common

disabled_panels = $(NULL)

enabled_panels += online-accounts

SUBDIRS = common $(enabled_panels)
DIST_SUBDIRS = $(SUBDIRS) $(disabled_panels)

-include $(top_srcdir)/git.mk
