Wordpress on OpenShift
======================

This repository borrows some of the techniques used in the official upstream
OpenShift wordpress-example repository. However, this repository aims for a
clear separation between data and code. It is expected that you will manage
all customizations as a set of logical changes (git commits) on top of this
repository. When a new release is pushed to this repo, you just rebase your
local changes on top of the new commit. I will also tag each Wordpress
release so that you can easily move (via rebase) between versions.
