These are some ideas that I have to build, some partially worked/working on, some never touched.

## Ideas

Ideas that have not been worked on yet. Please do ping me if you've started any work, so that I don't have to repeat :)

<details>
<summary>WebTorrent Online Player</summary>
#webtorrent, #torrent, #webapp

Integrate WebTorrent with an online web player, no server backends, just full frontend. Should allow to play multiple files in a torrent too

Sub Idea: Integrate it with [p2pt](https://github.com/subins2000/p2pt) to fetch movie torrents from yify API which will finally result in a Torrent Netflix. The ways to circumvent censorship and ISP blocking will be interesting to work on.
</details>

<details>
<summary>WebRTC Apps Offline in Android</summary>

\#webtorrent, \#android, \#game

Run [WebTorrent tracker](https://github.com/OpenWebTorrent/openwebtorrent-tracker) in Android, connect devices offline to make a mesg network and run offline WebRTC apps. As a demo to start working with, try to bring [Vett](https://github.com/subins2000/vett) or [WebDrop](https://github.com/subins2000/WebDrop) as an offline Android webview app.

Each device in the internet-less hotspot network would start a tracker or the main hotspot device starts a tracker. The Tracker IP & Port of these devices should be given to the webapp to access. The question is whether IP of devices in the network can be found out.
</details>

<details>
<summary>Torrent Seed Helper</summary>

\#webtorrent, \#torrent, \#webapp

A website where users can submit magnet links to a **list** to request seeders. The website has a "Help" page where people who want to help can start downloading those torrents in the **list** and seed forever. Why would they do that ? Pure love, they can use the site in their need too.
</details>
