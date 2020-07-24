# spec-files-extra
RPM style build scripts to compile and create IPS packages for Solaris / OmniOSce / OpenIndiana

This will be made the new master repository for spec files. The old repository on sourceforge will be synced regularly, but be set read-only.
The old wiki on sourceforge may be recreated here to give help to users and maintainers.

What does a "RPM spec file" do? It is used by the tool "pkgbuild" and contains Download-URL, patch instructions, configure, make, install steps. Finally it defines the contents of an IPS package that installs on Solaris 11, OmniOSce and OpenIndiana.
The main advantage is, you write one spec file and share this valuable work by maintainers across all operating systems.

For select packages there is an automatic build system (CI), so those numerous small version bumps get automatically built and uploaded to the IPS resporities here: https://sfe.opencsw.org/quickrepolinks

If you can help setting up this git repository, know how to setup automatic sync from github -> SVN/sourceforge, then please drop me a note on sfepackages@gmail.com or on twitter @sfepackages

For news see the workbench articles on the blog: https://sfe.opencsw.org

Regards
tomww
