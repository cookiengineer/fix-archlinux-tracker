
# Fix missing ArchLinux Security Tracker AVG

The ArchLinux Security Tracker is missing a bunch of issues, which usually were for
EOL software/packages where the maintainers deleted the issues due to not being able
to fix them.

So technically, they are still valid and the software with that outdated software is
still affected by the vulnerabilities.

This is the attempt to restore at least some of them for the [Vulnerabilities database](https://github.com/tholian-network/vulnerabilities)
by using the `web.archive.org`.

The issues were manually ported to JSON, because there weren't enough to justify writing
a custom scraper adapter for that use case.


# License

WTFPL

