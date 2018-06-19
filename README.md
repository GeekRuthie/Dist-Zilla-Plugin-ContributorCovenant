# NAME

Dist::Zilla::Plugin::ContributorCovenant - Add Contributor Covenant as Code of Conduct

# DESCRIPTION

`Dist::Zilla::Plugin::ContributorCovenant` adds the Contributor
Covenant to your CPAN build as `CODE_OF_CONDUCT.md`. It pulls
email address of first author from `dist.ini`. If none found,
it will type "GitHub / RT" instead.

# SYNOPSIS

Add this one line to your dist.ini.

    [ContributorCovenant]

# AUTHOR

Kivanc Yazan `<kyzn at cpan.org>`

# COPYRIGHT AND LICENSE

This software is copyright (c) 2018 by Kivanc Yazan.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.

# ATTRIBUTION

\- This module is based heavily on [Dist::Zilla::Plugin::Covenant](https://metacpan.org/pod/Dist::Zilla::Plugin::Covenant).

\- Covenant text is taken from https://www.contributor-covenant.org/version/1/4/code-of-conduct.md.

# SEE ALSO

\- Contributor Covenant, https://www.contributor-covenant.org/

\- VM Brasseur's "The Importance of Ecosystem" Keynote, https://archive.org/details/yatpc2018-ecosystem
