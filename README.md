# NAME

Dist::Zilla::PluginBundle::OYOULE - Dist::Zilla plugin configuration for Author/OYOULE

# VERSION

version 1.0.0

# SYNOPSIS

In your dist.ini

    [@OYOULE]
    dist        = Example-Distribution
    use_github  = 0
    use_darkpan = 1

# DESCRIPTION

A personal plugin bundle for [Dist::Zilla](https://metacpan.org/pod/Dist%3A%3AZilla).

# OPTIONS

- `dist`

    The name of the distribution.

    Required.

- `use_darkpan`

    Boolean indicating whether or not to release the distribution
    to a private CPAN mirror.

    Defaults to 0.

    When true, [Dist::Zilla::Plugin::UploadToDarkPAN](https://metacpan.org/pod/Dist%3A%3AZilla%3A%3APlugin%3A%3AUploadToDarkPAN) is enabled.
    When false, [Dist::Zilla::Plugin::UploadToCPAN](https://metacpan.org/pod/Dist%3A%3AZilla%3A%3APlugin%3A%3AUploadToCPAN) is enabled.

- `use_github`

    Boolean indicating whether or not the distribution lives
    on GitHub.

    Defaults to 1.

    When false, the repo metadata will instead point to my
    private git instance.

# SEE ALSO

- [Dist::Zilla](https://metacpan.org/pod/Dist%3A%3AZilla)
- [Dist::Zilla::Plugin::UploadToCPAN](https://metacpan.org/pod/Dist%3A%3AZilla%3A%3APlugin%3A%3AUploadToCPAN)
- [Dist::Zilla::Plugin::UploadToDarkPAN](https://metacpan.org/pod/Dist%3A%3AZilla%3A%3APlugin%3A%3AUploadToDarkPAN)

# AUTHOR

Oliver Youle <oliver@youle.io>

# COPYRIGHT AND LICENSE

This software is Copyright (c) 2025 by Oliver Youle.

This is free software, licensed under:

    The GNU General Public License, Version 3, June 2007
