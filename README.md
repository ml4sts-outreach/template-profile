# Sphinx Profile Page

This is is a template for a resume/ personal portfolio, built with Sphinx! Based on [Chris Holdgraf's](https://github.com/choldgraf/choldgraf.github.io)

This template is designed for use with the [ml4sts lab]
<!-- link instructions -->


## To work with this repo offline
The easiest way to build the website is to use `nox`, which handles all of the environment generation automatically.
To do so, follow these steps:

1. Install `nox`.

   ```shell
   pip install -U nox
   ```
2. Run `tox`

   ```shell
   nox -s docs
   ```

this should install a Sphinx environment and build the site, putting the output files in `_build/html`.

To run a live webserver that will auto-build and reload when you make changes, run:

```shell
nox -s docs-live
```
