These are some ideas that I have to build, some partially worked/working on, some not touched. Suggestions, PRs to everything welcome!

## Ideas

Ideas that have not been worked on yet. Please do ping me if you've started any work, so that I don't have to repeat :)

<details>
<summary>WebTorrent Online Player</summary>
<p>#webtorrent, #torrent, #webapp</p>

Integrate WebTorrent with an online web player, no server backends, just full frontend. Should allow to play multiple files in a torrent too

Sub Idea: Integrate it with [p2pt](https://github.com/subins2000/p2pt) to fetch movie torrents from yify API which will finally result in a Torrent Netflix. The ways to circumvent censorship and ISP blocking will be interesting to work on.
</details>

<details>
<summary>Torrent Seed Helper</summary>
<p>#webtorrent, #torrent, #webapp</p>

A website where users can submit magnet links to a **list** to request seeders. The website has a "Help" page where people who want to help can start downloading those torrents in the **list** and seed forever. Why would they do that ? Pure love, they can use the site in their need too.
</details>

<details>
<summary>Decentralized Torrent Search Engine</summary>
<p>#webtorrent, #torrent, #webapp</p>
  
2 different ways to do this :
  
* Proxy search queries via [p2pt](https://github.com/subins2000/p2pt) to [YIFY API](https://yts.mx/api). This is decentralized proxying. Caching search results by each proxy will be an enhancement.
* Make a [BIP39](https://iancoleman.io/bip39/) like wordlist for search queries. Suppose a query is `Ubuntu Beaver`, the query is split by whitespace, ordered to `Beaver Ubuntu` and a hash is made. Peers searching the same query or providing result for the query can be accessed by a torrent announce with the hash and results obtained. A search result provider has to keep seeding their results forever tho. This solution can work right in the browser (p2pt) with no backends.
</details>

## Working On

Ideas that I have done atleast 5% work on currently, but have not yet released to a stable state.

<details>
<summary>Find Photos You Are In Offline!</summary>
<p>#electronjs, #webapp</p>

Instead of having to upload your photos to an online service like Google Photos, what if there's a way to find photos with a particular face or faces is in. [FindMyPhotos on GitLab](https://gitlab.com/subins2000/findmyphotos).

* Cross platform
* Caching is done to speed up the process
* Not a full photo management software, see [KPhotoAlbum](https://www.kphotoalbum.org/) or [NextCloud Photos](https://github.com/nextcloud/photos).
* FMP can be used to sort photos, and later label them with a metadata so that other photo management software can pick them
</details>

<details>
<summary>Decentralized Access To Wikipedia</summary>
<p>#p2p, #webapp, #nodejs</p>
[Wikipeer on GitHub](https://github.com/subins2000/wikipeer/)
</details>

<details>
<summary>Internet-less WebRTC Apps in Android</summary>
<p>#webtorrent, #android, #game</p>

Run [WebTorrent tracker](https://github.com/OpenWebTorrent/openwebtorrent-tracker) in Android, connect devices offline to make a mesg network and run offline WebRTC apps. As a demo to start working with, try to bring [Vett](https://github.com/subins2000/vett) or [WebDrop](https://github.com/subins2000/WebDrop) as an offline Android webview app.

Each device in the internet-less hotspot network would start a tracker or the main hotspot device starts a tracker. The Tracker IP & Port of these devices should be given to the webapp to access. The question is whether IP of devices in the network can be found out.

[Dots on GtiLab](https://github.com/subins2000/dots)
</details>

<details>
<summary>Varnam Indic Language Editor</summary>
<p>#webapp, #linux</p>

Make an online indic language input editor with [varnamd](https://github.com/varnamproject/varnamd) API (also [varnamproject.com public API](https://api.varnamproject.com)). Possibly intergate [mlmorph-spellchecker](https://gitlab.com/smc/mlmorph-spellchecker). This editor can then be used for [Varnam Flatpak](https://github.com/subins2000/varnam) with learnings from API.
</details>

## Stable

See [https://subinsb.com/projects](https://subinsb.com/projects/)
