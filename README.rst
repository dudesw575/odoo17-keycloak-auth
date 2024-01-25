.. image:: https://img.shields.io/badge/licence-GPL--3-blue.svg
    :target: http://www.gnu.org/licenses/gpl-3.0-standalone.html
    :alt: License: GPL-3

===================
Auth Keycloak
===================

Extends the built in `auth_oauth` module

Configuration
~~~~~~~~~~~~~

* When adding new Oauth2 Connection check box for Keycloak
* Mapper on keycloak server for the client, map email to user_id

Installation
==========

* Must be added through the addons directory
* Enable developer mode 
* Apps -> Update App List
* Search for Auth
* DO NOT ACTIVATE default Oauth2 Module, only activate the one with Keycloak in name

Maintainer
==========

This module is maintained by Dylan Neves.