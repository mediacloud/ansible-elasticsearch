# NOTE!

This is a fork (with some Ubuntu fixes) of a fork (with ES 8.x
support) of the old (no longer supported) elastic supplied ansible
role for installing ES 7.x.

It has been kept in its original form in case upstream fixes become
available, for transparency regarding who changed what and when, and
to encourage leaving it alone (avoiding temptation to "improve" it).

It's used by `mediacloud/newsscribe-ansible`

NOTE!!!! Installs elasticsearch version 8.17.3, accordingly
jvm.options.j2 has been updated to the version from that release.
*BUT* files not used at Media Cloud have NOT been updated!
