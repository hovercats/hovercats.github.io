I have several notable projects:

- [rcinit](https://github.com/hovercats/rcinit)
  - a really small init script, written in plan9's rc shell
  - inspired by [shinit](https://github.com/cemkeylan/shinit), [sinit](http://core.suckless.org/sinit) and the like, I really wanted to
write one in rc instead
- [shsm](https://github.com/hovercats/shsm)
  - I really wanted to get rid of busybox's runit, and have a service manager
written in POSIX sh.
  - I then found [svc](http://r-36.net/scm/svc/log.html), which was (mostly) exacly what I was looking for,
although, with some flaws. So I made (what I would call) improvements
- [rcsm](https://github.com/hovercats/rcsm)
  - Superseeding shsm, I wanted to step up my game from rcinit, and write
  something a bit more complicated than rcsm.
  - based on the same idea as shsm, I put together a service manager i roughly
half the size of shsm.
- [kiss-dumpsterfire](https://github.com/hovercats/kiss-dumpsterfire)
  - my KISS repo, which hosts just about all of the packages on my system.
