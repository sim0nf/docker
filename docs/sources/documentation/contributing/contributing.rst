Contributing to Docker
======================

Want to hack on Docker? Awesome! There are instructions to get you
started on the website: http://docker.io/gettingstarted.html

They are probably not perfect, please let us know if anything feels
wrong or incomplete.

Contribution guidelines
-----------------------

Pull requests are always welcome
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

We are always thrilled to receive pull requests, and do our best to
process them as fast as possible. Not sure if that typo is worth a pull
request? Do it! We will appreciate it.

If your pull request is not accepted on the first try, don't be
discouraged! If there's a problem with the implementation, hopefully you
received feedback on what to improve.

We're trying very hard to keep Docker lean and focused. We don't want it
to do everything for everybody. This means that we might decide against
incorporating a new feature. However, there might be a way to implement
that feature *on top of* docker.

Discuss your design on the mailing list
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

We recommend discussing your plans `on the mailing
list <https://groups.google.com/forum/?fromgroups#!forum/docker-club>`__
before starting to code - especially for more ambitious contributions.
This gives other contributors a chance to point you in the right
direction, give feedback on your design, and maybe point out if someone
else is working on the same thing.

Create issues...
~~~~~~~~~~~~~~~~

Any significant improvement should be documented as `a github
issue <https://github.com/dotcloud/docker/issues>`__ before anybody
starts working on it.

...but check for existing issues first!
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Please take a moment to check that an issue doesn't already exist
documenting your bug report or improvement proposal. If it does, it
never hurts to add a quick "+1" or "I have this problem too". This will
help prioritize the most common problems and requests.

Write tests
~~~~~~~~~~~

Golang has a great testing suite built in: use it! Take a look at
existing tests for inspiration.
