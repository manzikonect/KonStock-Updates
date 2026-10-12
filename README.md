# KonStock Updates

Official KonStock Windows x64 installers and update releases.

This repository contains release artifacts only. Application source, private
signing keys, licensing secrets and customer business data are not published here.

KonStock verifies update packages against an app-pinned RSA-PSS signing key and a
version-specific signed authorization manifest. This is separate from Windows
publisher/Authenticode signing. Windows warnings or security-policy restrictions
may remain; do not disable Windows security policies to run this application.

Back up business data before an initial installation. Install the latest testing
setup once to bootstrap the free update verifier. Version 1.0.6 added automatic
background checking and downloading after sign-in, with an Update ready notice.
Restart/install requires your explicit confirmation and safe database backups;
updates never silently install at startup or interrupt a sale.

Version 1.0.7 fixes a startup permission error before PIN sign-in and safe shutdown
of the sync service. If an older build fails to open, close it and run the latest
setup as an upgrade. Do not uninstall/delete the app's local data or licensing
state. An already completed activation should remain available; new computers
require separate one-time activation codes under the same Basic subscription.

[Latest testing release](https://github.com/manzikonect/KonStock-Updates/releases/latest)

This is a controlled-testing release. Physical multi-computer and installed-update
acceptance remains part of testing before unrestricted customer distribution.
