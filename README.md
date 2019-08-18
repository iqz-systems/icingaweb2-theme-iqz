IQZ Default Theme for Icinga Web 2
======================================

This is an example to give you an idea how to start modifying the theme
of Icinga Web 2 to your needs.

Requires:
* Icinga Web 2.5 or newer

Only a few things are tweaked right now:

* Main logo in the interface replaced by a corporate logo
* Colors of Icinga tuned for a corporate CI
* Login background changed

In every theme, the base theme of Icinga Web 2 is applied, and modifications need to be
added incrementally.

You can find the overall theme on [GitHub](https://github.com/Icinga/icingaweb2/tree/master/public/css/icinga)
or on your local system under `/usr/share/icingaweb2/public/css/icinga`.

## How to install

Install these theme repository like any other Icinga Web 2 module at:

    /usr/share/icingaweb2/modules/iqz-icingaweb2-theme
    
Enable the module:

    icingacli module enable iqz-icingaweb2-theme
    
Then you can select the theme in the admin or user UI.

Tweak it to your needs, you can also change the module name or
incorporate the files into your own module.