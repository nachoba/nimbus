size = 24x24
context = places
iconsdir = $(themedir)/$(size)/$(context)
icons_DATA = 				 		\
		application-x-executable.png 		\
		blockdev.png 		\
		bookmark-missing.png 		\
		bookmark.png 		\
		file.png 		\
		folder-drag-accept.png 		\
		folder.png 		\
		gnome-fs-ftp.png 		\
		gnome-fs-nfs.png 		\
		gnome-fs-share.png 		\
		gnome-fs-smb.png 		\
		gnome-fs-ssh.png 		\
		network-server.png 		\
		network-workgroup.png 		\
		pm-window-toggle.png 		\
		printer-group-favorites.png 		\
		printer-group-new.png 		\
		printer-group.png 		\
		printer-new.png 		\
		printer-search-group-new.png 		\
		printer-search-group.png 		\
		start-here.png 		\
		user-desktop.png 		\
		user-home.png 		\
		user-trash-full.png 		\
		user-trash.png 		\
		web.png
EXTRA_DIST = $(icons_DATA)

install-data-local: install-iconsDATA
	(cd $(DESTDIR)$(themedir)/$(size) && $(ICONMAP) -c $(context) -e $(iconsrcdir)/icons/my-mapping.xml)

uninstall-local:
	rm -Rf $(DESTDIR)$(themedir)/$(size)/$(context)
