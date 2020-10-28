# OpenID Connect SCHAC Codes

Add support for SCHAC codes in the OpenID ecosystem.

This module adds two fields to the user account and the corresponding OpenID Connect claims.

## Installation

Include the repository in your project's `composer.json` file:

    "repositories": [
        ...
        {
            "type": "vcs",
            "url": "https://github.com/EuropeanUniversityFoundation/openid_connect_schac_codes"
        }
    ],

Then you can require the package as usual:

    composer require euf/openid_connect_schac_codes

Finally, install the module:

    drush en openid_connect_schac_codes

## Usage

First check the configuration for the new fields under `/admin/config/people/accounts/form-display` and `/admin/config/people/accounts/display`. Then visit `/admin/config/services/openid-connect` to map the new user claims to the new fields in the user account.
