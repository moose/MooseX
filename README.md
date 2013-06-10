# NAME

MooseX - Document the MooseX namespace

# VERSION

version 0.001

# SYNOPSIS

    package MyClass;
    use Moose;
    use MooseX::SomeExtension;

    ...

# DESCRIPTION

The `MooseX::*` namespace is for _Moose extensions_, not a general space for
any module that happens to use [Moose](http://search.cpan.org/perldoc?Moose).

Usually, such modules will make use of [Moose::Exporter](http://search.cpan.org/perldoc?Moose::Exporter) to make their
extension available to the calling class. It may define a class or attribute
trait, apply a role, or perhaps provide sugar functions.

Things that do __not__ belong in the `MooseX::*` namespace are: classes that
use Moose for their OO, and packages that use [Moose::Role](http://search.cpan.org/perldoc?Moose::Role) to provide
implementation. Instead, name those modules for what they _do_ not how they
do it.

(This documentation is a preliminary placeholder for more information. Patches
welcome!)

# SUPPORT

Bugs may be submitted through [the RT bug tracker](https://rt.cpan.org/Public/Dist/Display.html?Name=MooseX)
(or [bug-MooseX@rt.cpan.org](mailto:bug-MooseX@rt.cpan.org)).
I am also usually active on irc, as 'ether' at `irc.perl.org`.

# SEE ALSO

- [Moose::Manual::MooseX](http://search.cpan.org/perldoc?Moose::Manual::MooseX)
- [MooseY](http://search.cpan.org/perldoc?MooseY)

# AUTHOR

Karen Etheridge <ether@cpan.org>

# COPYRIGHT AND LICENSE

This software is copyright (c) 2013 by Karen Etheridge.

This is free software; you can redistribute it and/or modify it under
the same terms as the Perl 5 programming language system itself.
