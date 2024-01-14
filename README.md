# guide to marsxplr #<br>
a guide to playing the game Mars Explorer long after its discontinuation<br>
<br>
## downloading Mars Explorer ##<br>
you can still download marsplxr from [the wayback machine page](http://web.archive.org/web/20151020124336/http://marsxplr.com/view-267)<br>
or you can download it from [lamps archive](https://gitea.moe/lamp/dat.marsxplr.com-mirror/src/branch/master/dat.marsxplr.com/222)<br>
<br>
## installing marsxplr ##<br>
marsxplr still more or less works on modern versions of windows,<br>
<br>
but it is not functional on newer versions of macos.<br>
you can run marsxplr using W.I.N.E up until macos catalina,<br>
which doesnt support 32 bit applications.<br>
<br>
you can only play marsxplr on linux using windows compatability layers,<br>
like W.I.N.E. or playonlinux.<br>
<br>
## playing marsxplr ##<br>
### whirlds ###<br>
pretty much all of the whirlds shown in the original whirld list are no longer being hosted,<br>
and cannot be played through traditional means,<br>
but fear not, many whirlds have been archived by [lamp](https://gitea.moe/lamp/whirlds)<br>
to play these whirlds you must copy a link to a "Whirld.utw" file (with some formatting changes)<br>
(if a whirld is hosted on something like github or gitea, make sure to get the raw file).<br>
for all whirlds, you must change the beginning "https" to "http" in order for it to work in marsxplr,<br>
and if there are any special characters in the whirld link, you must replace them with their html code counterparts,<br>
for example: space = %20, double quote = %34, apostraphe = %37.<br>
so<br>
```http://gitea.moe/lamp/whirlds/raw/branch/master/ibcf's World Backups/World Backups 2/Aubrey Falconer's Sky Bridge/Whirld.utw```<br>
for example would turn into<br>
```https://gitea.moe/lamp/whirlds/raw/branch/master/ibcf%27s%20World%20Backups/World%20Backups%202/Aubrey%20Falconer%27s%20Sky%20Bridge/Whirld.utw```.<br>
once you have a correctly formatted whirld link, paste it into the custom whirld url box and then play.<br>
if it failed to load, check if the you typed/formatted the url correctly.<br>
<br>
### joining/hosting ###<br>
now that the marsxplr master servers have been shut down, games will no longer show in the list,<br>
the only option for joining games is direct connect, so you need an ip address and a port number to join an active hosted game.<br>
<br>
again, as the master servers are shut down, you must port forward all games manually.<br>
you can do this by adding the udp and tcp port 2500 to your routers port forwarding settings,<br>
or you can enter 2500 udp/tcp into a portmapping software like [upnp portmapper](https://sourceforge.net/projects/upnp-portmapper/)<br>
<br>
## conclusion<br>
mars xplr is definitely not as alive as it once was, but it is not lost forever.<br>
its still possible to relive the nostalgia, with some work.<br>
<br>
if you have anything you would like to add/change in this guide, please make a pull request.<br>
if you have any further questions, please direct them to the awesome people on the [terran labs discord](https://discord.gg/dxTFZRM)<br>
i hope this guide helps give you the opportunity to relive the martian experience after all these years.
