# NAME

__list-installed-perl-modules__ - list up installed Perl modules

# SYNOPSIS

__list-installed-perl-modules__
\[__\-f__ _format_\]
\[__\-v__ | __\--verbose__\]

__list-installed-perl-modules__ __\-h__ | __\--help__ | __\-?__

    $ list-installed-perl-modules
    $ list-installed-perl-modules -f hash

# DESCRIPTION

This script lists up installed Perl modules and outputs as cpanfile or hash format.

# OPTIONS

- __\-f__ _format_, __\--format__ _format_

    Specify output format: "cpanfile" or "hash". Default is "cpanfile".

- __\-v__, __\--verbose__

    Enable verbose mode.

# SEE ALSO

[ExtUtils::Installed](https://metacpan.org/pod/ExtUtils::Installed)

# AUTHOR

HIROSE Masaaki <hirose31@gmail.com>
