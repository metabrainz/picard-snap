<h1 align="center">
  <img
  src="https://raw.githubusercontent.com/metabrainz/picard-snap/main/snap/gui/picard.svg" alt="MusicBrainz Picard">
  <br />
  MusicBrainz Picard
</h1>

<p align="center">This is the snap for <a href="https://picard.musicbrainz.org/">MusicBrainz Picard</a>, the official MusicBrainz audio tagger. It works on Ubuntu, Fedora, Debian, and other major Linux
distributions.</p>

<p align="center">
<a href="https://snapcraft.io/picard">
  <img alt="Get it from the Snap Store" src="https://snapcraft.io/static/images/badges/en/snap-store-black.svg" />
</a>
</p>


## Install

    sudo snap install picard

Picard installed as a Snap is running inside a sandbox and thus it does not have full access to all files and folders on your system. By default Picard has access to your home folder. You can additionally give it access to removable media by running the following command on a terminal:

    snap connect picard:removable-media

([Don't have snapd installed?](https://snapcraft.io/docs/tutorials/install-the-daemon/))

See also the [Installing with Snap](https://picard-docs.musicbrainz.org/en/latest/getting_started/download.html#installing-with-snap) instructions in the MusicBrainz Picard documentation.

Please see the [Picard download page](https://picard.musicbrainz.org/downloads/) for installing Picard
on other platforms.


## Running

The Picard Snap should show up as an application "MusicBrainz Picard" in your desktop environment. You can also start it from a terminal:

    snap run picard
    
![MusicBrainz Picard main window](https://raw.githubusercontent.com/metabrainz/picard-snap/main/mainscreen-linux-gnome.png)

Picard 3 also allows managing plugins from command line. Run the following command for more information on how to use this:

    snap run picard.plugins --help


## Support and issue reporting

Please report all bugs and feature requests in the
[MusicBrainz issue tracker](https://tickets.metabrainz.org/projects/PICARD/issues).
If you need support in using Picard please read the [documentation](https://picard-docs.musicbrainz.org/)
first and have a look at the [MusicBrainz community forums](https://community.metabrainz.org/c/picard).
