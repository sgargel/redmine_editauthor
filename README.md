Redmine Edit Issue Author
===================

Redmine plugin that allows to edit issue author.


Installation
------------

Follow standard Redmine plugin installation procedure.

  * Move `redmine_editauthor/` to `$REDMINE/plugins/`.


Configuration
-------------
Set following permission for roles:

 * "Edit author"

    Authorized users will be able to edit issue author by simply changing field
    in edit form.

 * "Set original author"

    Authorized users will be able to set a different issue author when creating new issue.

 * "Can't be set as author"

    Users with this permission can't be choosed as author.


Requirements
------------

Since this program depend on another software, it was written with compatibility
in mind to keep it functional across many version of software it uses.

  * Redmine (2.0+)
  * Redmine (3.0+)
