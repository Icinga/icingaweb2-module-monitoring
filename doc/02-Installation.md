<!-- {% if index %} -->

# Installing Monitoring Module <a id="monitoring-module-installation"></a>

This module is provided with the Icinga Web 2 (version <2.13) package and does
not need any extra installation step.

If you are using a higher version, the recommended way to install the Monitoring module is to use prebuilt packages for
all supported platforms from our official release repository.

Please follow the steps listed for your target operating system,
which guide you through setting up the repository and installing the Monitoring module.
<!-- {% else %} -->
<!-- {% if not icingaDocs %} -->

## Installing the Package

If the [repository](https://packages.icinga.com) is not configured yet, please add it first.
Then use your distribution's package manager to install the `icingaweb2-module-monitoring` package
or install [from source](02-Installation.md.d/From-Source.md).
<!-- {% endif %} -->

This concludes the installation. Now proceed with the [configuration](03-Configuration.md).
<!-- {% endif %} -->
