subdir('icons')

gui_data = [
  'shell.ui',
  'shell.css'
]
install_data(gui_data, install_dir: pkgdatadir)

desktop_file = 'org.gnome.tweaks.desktop'
i18n.merge_file(desktop_file,
  input: desktop_file + '.in',
  output: desktop_file,
  po_dir: '../po',
  install: true,
  install_dir: desktopdir,
  type: 'desktop'
)

appdata_file = 'org.gnome.tweaks.appdata.xml'
i18n.merge_file(appdata_file,
  input: appdata_file + '.in',
  output: appdata_file,
  po_dir: '../po',
  install: true,
  install_dir: appdatadir
)
