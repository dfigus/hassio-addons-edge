# TVHeadend Home Assistant Add-On

[![Release][release-shield]][release] ![Project Stage][project-stage-shield] ![Project Maintenance][maintenance-shield]

TVHeadend is a TV streaming server and recorder.

## About

TVHeadend is a TV streaming server and recorder supporting:
DVB-S, DVB-S2, DVB-C, DVB-T, DVB-T2, ATSC, ISDB-T, IPTV, SAT>IP and HDHomeRun
as input sources.
TVHeadend offers the HTTP (VLC, MPlayer), HTSP (Kodi, Movian) and SAT>IP streaming.

Multiple EPG sources are supported such as
over-the-air DVB and ATSC including OpenTV DVB extensions, XMLTV, PyXML.

As TVHeadend stopped to create releases in 2017, this addon-on builds TVHeadend from
the master branch.

This add-on has the following additional software preinstalled:

- [picons][picons]: Channel icons
- [Comskip][comskip]: A tool to mark commercials in recordings (autoskipped in Kodi)
- [Comchap & Comcut][comchap]: Utilities to add chapters or cut commercials based on detected commercials from Comskip
- [StreamLink][streamlink]
- [WebGrab++][wg++]: A XMLTV EPG grabber for many sites. Useful in case OTA EPG is not sufficient.

[picons]: https://github.com/picons/picons
[comskip]: https://github.com/erikkaashoek/Comskip
[comchap]: https://github.com/BrettSheleski/comchap
[streamlink]: https://streamlink.github.io/
[wg++]: http://www.webgrabplus.com/
[forum-shield]: https://img.shields.io/badge/community-forum-brightgreen.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2025.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-production%20ready-brightgreen.svg
[release-shield]: https://img.shields.io/badge/version-4072670-blue.svg
[release]: https://github.com/dfigus/addon-tvheadend/tree/4072670