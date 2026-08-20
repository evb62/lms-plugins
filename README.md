# My plugins for Lyrion Music Server (LMS)

## Queue Consume
A track leaves the play queue once it has
finished playing or has been skipped with 'Next' (and optionally with 'Previous').

After installing the plugin, other settings will be available in the Player WebUI -> Extra Settings.

Plugin page:
[Queue Consume](https://github.com/evb62/lms-queue-consume)

## DSD to PCM Transcoding

Background: a music library where some parts are in PCM audio (FLAC, for instance), others are in DSD audio (DSD compressed to WavPack/wv). There is no software volume control in Lyrion for DSD.

This plugin provides on-the-fly transcoding of DSD files compressed in WavPack to PCM, enabling use of software volume control.
After installing the plugin, other settings will be available in the Player WebUI -> Extra Settings.

Plugin page:
[DSD to PCM Transcoding](https://github.com/evb62/lms-dsdtopcm)

## Installation

Scroll to the end of the "Manage Plugins" page in the LMS WebUI. Find the "Additional Repositories" and fill the line with the repository address:
https://raw.githubusercontent.com/evb62/lms-plugins/main/public.xml.

Then enable the plugin.
