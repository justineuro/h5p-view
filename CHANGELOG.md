# CHANGELOG 

## v0.0.3 (2026-07-24)
* Refactor the server starter section of the script
  * Added support for versioned interpreters (e.g., `python3.121`, `php8.4`)
  * Replaced hardcoded checks with flexible pattern matching
  * Improved handling when `$SERVER` is unset or unsupported
  * Updated `README` with usage examples and notes

This change was suggested by an [Issue](https://github.com/justineuro/h5p-view/issues/1#issue-4958621464) raised by [@aretaon](https://github.com/aretaon) and refined with the assistance of [Microsoft Copilot](copilot.microsoft.com).

## v0.0.4 (2026-07-26)
* Change the link of the `Mathjax 4` source to make it non-version specific.