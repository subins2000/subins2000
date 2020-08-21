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
<summary>Internet-less WebRTC Apps in Android</summary>

\#webtorrent, \#android, \#game

Run [WebTorrent tracker](https://github.com/OpenWebTorrent/openwebtorrent-tracker) in Android, connect devices offline to make a mesg network and run offline WebRTC apps. As a demo to start working with, try to bring [Vett](https://github.com/subins2000/vett) or [WebDrop](https://github.com/subins2000/WebDrop) as an offline Android webview app.

Each device in the internet-less hotspot network would start a tracker or the main hotspot device starts a tracker. The Tracker IP & Port of these devices should be given to the webapp to access. The question is whether IP of devices in the network can be found out.
</details>

<details>
<summary>Torrent Seed Helper</summary>

\#webtorrent, \#torrent, \#webapp

A website where users can submit magnet links to a **list** to request seeders. The website has a "Help" page where people who want to help can start downloading those torrents in the **list** and seed forever. Why would they do that ? Pure love, they can use the site in their need too.
</details>

<details>
<summary>Decentralized Torrent Search Engine</summary>
2 ways to do this :
* Proxy search queries via [p2pt](https://github.com/subins2000/p2pt) to [YIFY API](https://yts.mx/api). This is decentralized proxying. Caching search results by each proxy will be an enhancement.
* Make a [BIP39](https://iancoleman.io/bip39/) like wordlist for search queries. Suppose a query is `Ubuntu Beaver`, the query is split by whitespace, ordered to `Beaver Ubuntu` and a hash is made. Peers searching the same query or providing result for the query can be accessed by a torrent announce with the hash and results obtained. A search result provider has to keep seeding their results forever tho. This solution can work right in the browser (p2pt) with no backends.
</details>
