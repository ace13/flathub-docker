# Docker images for building Flatpak

These Docker images contain the necessary bits for running `flatpak-builder`
and generating a Flatpak application repository or bundle.

They are divided into the following layers:

 - `base/` - the base Docker image, containing the necessary bits for
   running `flatpak-builder`
 - `fdo-1.6/` - a Docker image containing the Freedesktop 1.6 Platform
   and SDK runtimes
 - `gnome-3.24/` - a Docker image containing the GNOME 3.24 Platform
   and SDK runtimes
