# TPC's FreeDOS PC DOS 1.1 HomageEdition

This is just a fun project, replicating the feature
set of [IBM PC DOS 1.1](https://en.wikipedia.org/wiki/IBM_PC_DOS#PC_DOS_1.x) using [FreeDOS](https://freedos.org). No pun intended.

# Disk Images

A set of premade disk images are available:

* [160K](Disk%20Images/160K)
* [180K](Disk%20Images/180K)
* [360K](Disk%20Images/360K)


# What's included?

Basically, all binary files found on the original IBM PC DOS 1.1
floppy disk were replaced by their FreeDOS counterparts.

# What's NOT included?

I left-out the .BAS files found in IBM PC DOS 1.1,
and also `basic.com` and `basica.com`.

I could have included [GWBASIC](https://github.com/microsoft/GW-BASIC),
as this was opensourced by Microsoft, but I left it out for now.

No modern-day basic replacement was included because of the size.

I wanted to make it fit to 160k, 180k and 360k media.


# Why? What for? Sounds useless?

It's an homage to IBM PC DOS 1.1.
I just acquired an original and almost pristine set of PC DOS 1.1
and had this weird idea of making a modern-day'ish FreeDOS homage.

There's no use, and no other reason than that except just
making it happen for fun.


# But what about all the other FreeDOS utilities? What about fdisk, ....?

As I said, it's an homage to IBM PC DOS 1.1, and as such it's a 1:1
replacement of the tools and commands that were available in this release.

So I didn't include anything else on purpose.
It's the idea to experience FreeDOS the way as if it were PC DOS 1.1.


# How to make it myself?

There's this [MKPCDHDE.BAT](MKPCDHDE.BAT) file, which works by copying
the files found in `C:\FreeDOS\BIN` onto the selected floppy disk media.

So you need a running FreeDOS on your hard drive, that's all,
all the files are directly taken from there.

I used FreeDOS 1.3 as a basic, but any release of FreeDOS will work.

