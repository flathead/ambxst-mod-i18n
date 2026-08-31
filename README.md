# Ambxst runtime translations

This package adds runtime language switching and English, Russian, and Spanish
translations to Ambxst. It is also the shared localization dependency for UI
mods in the [Ambxst community mod collection](https://github.com/flathead/ambxst-mods).

## Install

Open **Settings → Mods**, paste this repository URL into **Package source**, and
select **Install**:

```text
https://github.com/flathead/ambxst-mod-i18n.git
```

Enable the installed package and restart Ambxst when prompted. If another mod
requires translations, its **Install required mods** action performs these steps
for the dependency and leaves the selected mod disabled until you enable it.

## Package contents

The package is a patch against the tested Ambxst base revision recorded in
`ambxst.mod.json`. It adds the translation service, locale files, and calls from
the current Ambxst surfaces. The mod manager remains usable in English when this
package is absent or disabled.
