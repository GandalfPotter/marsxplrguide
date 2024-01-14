# marsxplrguide
a guide to playing the game Mars Explorer long after its discontinuation

## downloading Mars Explorer ##
you can still download marsplxr from [the wayback machine page](http://web.archive.org/web/20151020124336/http://marsxplr.com/view-267)
or you can download it from [lamps archive](https://gitea.moe/lamp/dat.marsxplr.com-mirror/src/branch/master/dat.marsxplr.com/222)

## installing marsxplr ##
marsxplr still more or less works on modern versions of windows,

but it is not functional on newer versions of macos.
you can run marsxplr using W.I.N.E up until macos catalina,
which doesnt support 32 bit applications.

you can only play marsxplr on linux using windows compatability layers,
like W.I.N.E. or playonlinux.

## playing marsxplr ##
### whirlds ###
pretty much all of the whirlds shown in the original whirld list are no longer being hosted,
and cannot be played through traditional means,
but fear not, many whirlds have been archived by [lamps](https://gitea.moe/lamp/whirlds)
to play these whirlds you must copy a link to a "Whirld.utw" file (with some formatting changes)
(if a whirld is hosted on something like github or gitea, make sure to get the raw file).
for all whirlds, you must change the beginning "https" to "http" in order for it to work in marsxplr,
and if there are any special characters in the whirld link, you must replace them with their html code counterparts,
for example: space = %20, double quote = %34, apostraphe = %37.
so "http://gitea.moe/lamp/whirlds/raw/branch/master/ibcf's World Backups/World Backups 2/Aubrey Falconer's Sky Bridge/Whirld.utw" for example would turn into "https://gitea.moe/lamp/whirlds/raw/branch/master/ibcf%27s%20World%20Backups/World%20Backups%202/Aubrey%20Falconer%27s%20Sky%20Bridge/Whirld.utw".
once you have a correctly formatted whirld link, paste it into the custom whirld url box and then play.
if it failed to load, check if the you typed/formatted the url correctly.

### joining/hosting ###
now that the marsxplr master servers have been shut down, games will no longer show in the list,
the only option for joining games is direct connect, so you need an ip address and a port number to join an active hosted game.

again, as the master servers are shut down, you must port forward all games manually.
you can do this by adding the udp and tcp port 2500 to your routers port forwarding settings,
or you can enter 2500 udp/tcp into a portmapping software like [upmp portmapper](https://sourceforge.net/projects/upnp-portmapper/)

## conclusion
mars xplr is definitely not as alive as it once was, but it is not lost forever.
its still possible to relive the nostalgia, with some work.

if you have anything you would like to add/change in this guide, please make a pull request.
if you have any further questions, please direct them to the awesome people on the [terran labs discord](https://discord.gg/dxTFZRM)
i hope this guide helps give you the opportunity to relive the martian experience after all these years.
