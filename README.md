Table of Contents
=================

# What You Get From This control-repo

This repository is the Service Master's  control-repo to be used with Puppet Enterprise Code Manager.

The major points are:
 - An environment.conf that correctly implements:
   - A site directory for roles, profiles, and any custom modules for your organization.
   - A config_version script.
 - Provided config_version scripts to output the commit of code that your agent just applied.
 - Basic example of roles/profiles code.
 - Example hieradata directory with pre-created common.yaml and nodes directory.
   - These match the default hierarchy that ships with PE.
