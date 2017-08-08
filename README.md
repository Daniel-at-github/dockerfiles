# dockerfiles

[![Travis CI](https://travis-ci.org/jessfraz/dockerfiles.svg?branch=master)](https://travis-ci.org/jessfraz/dockerfiles)

This is a repo to hold various Dockerfiles for images I create.

I try to make sure each has a command at the top for running it, if a file you are looking at does not have a command, please pull request it!

Almost all of these live on dockerhub under [jess](https://hub.docker.com/u/jess/). Because you cannot use notary with autobuilds on dockerhub I also build these continuously on a private registry at [r.j3ss.co](https://r.j3ss.co/) for public download. (You're welcome.)

You may also want to checkout my [dotfiles](https://github.com/jessfraz/dotfiles), specifically the aliases for all these files which are here: [github.com/jessfraz/dotfiles/blob/master/.dockerfunc](https://github.com/jessfraz/dotfiles/blob/master/.dockerfunc).

Container                                    | Description
-------------------------------------------- | ------------------------------------------------------------------------------------------------------------------
[ab](./ab)                                   |
[afterthedeadline](./afterthedeadline)       |
[android-tools](./android-tools)             |
[ansible](./ansible)                         |
[apt-file](./apt-file)                       |
[atom](./atom)                               |
[audacity](./audacity)                       |
[awscli](./awscli)                           |
[beeswithmachineguns](./beeswithmachineguns) |
[buttslock](./buttslock)                     |
[camlistore](./camlistore)                   |
[cathode](./cathode)                         | That super old school terminal.
[certbot](./certbot)                         |
[cf-reset-cache](./cf-reset-cache)           |
[checkup](./checkup)                         |
[cheese](./cheese)                           |
[chrome](./chrome)                           | Pretty sure everyone knows what chrome is, but my image comes with flash and the google talk plugin so you can do.
[chromium](./chromium)                       |
[clair](./clair)                             |
[clean-registry](./clean-registry)           |
[cli53](./cli53)                             |
[cloudapp](./cloudapp)                       |
[commit-watcher](./commit-watcher)           |
[consul](./consul)                           |
[couchpotato](./couchpotato)                 |
[cpuminer](./cpuminer)                       |
[curl](./curl)                               |
[dcos-cli](./dcos-cli)                       |
[debootstrap](./debootstrap)                 |
[distcc](./distcc)                           |
[doctor](./doctor)                           |
[dunnet](./dunnet)                           |
[evince](./evince)                           |
[firefox](./firefox)                         |
[fontpatcher](./fontpatcher)                 |
[foss-heartbeat](./foss-heartbeat)           |
[gcalcli](./gcalcli)                         |
[gcc](./gcc)                                 |
[gcloud](./gcloud)                           |
[geary](./geary)                             |
[gimp](./gimp)                               |
[gitiles](./gitiles)                         |
[gitserver](./gitserver)                     |
[gitsome](./gitsome)                         |
[gixy](./gixy)                               |
[glxgears](./glxgears)                       |
[gmail-britta](./gmail-britta)               |
[golang-softhsm2](./golang-softhsm2)         |
[gparted](./gparted)                         | Partition your device in a container.
[guetzli](./guetzli)                         |
[hollywood](./hollywood)                     |
[htop](./htop)                               |
[httpie](./httpie)                           |
[icedove](./icedove)                         |
[iceweasel](./iceweasel)                     |
[imagemagick](./imagemagick)                 |
[imagemin](./imagemin)                       |
[inkscape](./inkscape)                       |
[irssi](./irssi)                             | Best IRC client.
[john](./john)                               |
[jq](./jq)                                   |
[keepass2](./keepass2)                       |
[keepassxc](./keepassxc)                     |
[kernel-builder](./kernel-builder)           |
[kvm](./kvm)                                 |
[libreoffice](./libreoffice)                 |
[libvirt-client](./libvirt-client)           |
[lilyterm](./lilyterm)                       |
[lpass](./lpass)                             |
[lynx](./lynx)                               | The browser everyone loves (to hate). but secretly I love
[mailman](./mailman)                         |
[masscan](./masscan)                         |
[mdp](./mdp)                                 |
[mesos-dev](./mesos-dev)                     |
[metasploit](./metasploit)                   |
[micro](./micro)                             |
[mitmproxy](./mitmproxy)                     |
[mop](./mop)                                 |
[mpd](./mpd)                                 |
[mpsyt](./mpsyt)                             |
[mutt](./mutt)                               | The text based email client that rules!
[ncmpc](./ncmpc)                             |
[neoman](./neoman)                           |
[nerdy](./nerdy)                             |
[nes](./nes)                                 |
[netcat](./netcat)                           |
[nginx-extras](./nginx-extras)               |
[nmap](./nmap)                               |
[node-sonos](./node-sonos)                   |
[no_new_privs](./no_new_privs)               |
[notify-osd](./notify-osd)                   |
[oauth2-proxy](./oauth2-proxy)               |
[openvpn](./openvpn)                         |
[pandoc](./pandoc)                           |
[pivman](./pivman)                           |
[plex-home-theater](./plex-home-theater)     |
[plexpy](./plexpy)                           |
[pms](./pms)                                 |
[pond](./pond)                               |
[pop](./pop)                                 |
[postfix](./postfix)                         |
[powershell](./powershell)                   |
[privoxy](./privoxy)                         |
[pulseaudio](./pulseaudio)                   |
[rainbowstream](./rainbowstream)             | Awesome text based twitter client.
[rdesktop](./rdesktop)                       |
[remmina](./remmina)                         |
[ricochet](./ricochet)                       |
[routersploit](./routersploit)               |
[rstudio](./rstudio)                         |
[s3cmd](./s3cmd)                             |
[scudcloud](./scudcloud)                     |
[shellcheck](./shellcheck)                   |
[shorewall](./shorewall)                     |
[sickbeard](./sickbeard)                     |
[skype](./skype)                             | The other video conferencer. This relies on running pulseaudio also in a container.
[slack](./slack)                             |
[slapd](./slapd)                             |
[snort](./snort)                             |
[spotify](./spotify)                         | All the 90s hits you ever wanted and more.
[spotify-wine](./spotify-wine)               |
[ssr](./ssr)                                 |
[stress](./stress)                           |
[sublime-text-3](./sublime-text-3)           |
[t](./t)                                     |
[tarsnap](./tarsnap)                         |
[telize](./telize)                           |
[telnet](./telnet)                           |
[termboy](./termboy)                         |
[tetris](./tetris)                           |
[texlive](./texlive)                         |
[tomahawk](./tomahawk)                       |
[tor-browser](./tor-browser)                 | Because Tor, duh!
[tor-messenger](./tor-messenger)             |
[tor-proxy](./tor-proxy)                     |
[tor-relay](./tor-relay)                     |
[tor-router](./tor-router)                   |
[traceroute](./traceroute)                   |
[transmission](./transmission)               |
[transmission-ui](./transmission-ui)         |
[travis](./travis)                           |
[vagrant](./vagrant)                         |
[vault](./vault)                             |
[virtualbox](./virtualbox)                   |
[virt-viewer](./virt-viewer)                 |
[vlc](./vlc)                                 |
[vscode](./vscode)                           |
[wargames](./wargames)                       |
[watchman](./watchman)                       |
[weechat](./weechat)                         |
[wee-slack](./wee-slack)                     |
[wine](./wine)                               |
[wireguard](./wireguard)                     |
[wireshark](./wireshark)                     |
[wrk](./wrk)                                 |
[ykpersonalize](./ykpersonalize)             |
[yubico-piv-tool](./yubico-piv-tool)         |
[znc](./znc)                                 |
[zookeeper](./zookeeper)                     |
[zsh](./zsh)                                 |
