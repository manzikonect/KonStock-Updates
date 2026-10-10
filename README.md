# KonStock Updates

Official KonStock Windows x64 installers and update releases.

This repository contains release artifacts only. Application source, private
signing keys, licensing secrets and customer business data are not published here.

KonStock verifies update packages against an app-pinned RSA-PSS signing key and a
version-specific signed authorization manifest. This is separate from Windows
publisher/Authenticode signing. Windows warnings or security-policy restrictions
may remain; do not disable Windows security policies to run this application.

Back up business data before an initial installation. Version 1.0.5 bootstraps the
free update verifier; earlier unsigned testing builds require this initial installer.
Subsequent authorized releases can be downloaded from the installed app.

This is a controlled-testing release. Physical multi-computer and installed-update
acceptance remains part of testing before unrestricted customer distribution.
