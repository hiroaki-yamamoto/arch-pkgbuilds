# Linux Kernel 4.4 LTS PKGBUILD

## What's this?
This is a [PKGBUILD](https://wiki.archlinux.org/index.php/PKGBUILD) to build
Linux Kernel 4.4.x LTS

## Why did I create this package?
Because I have troubles since kernel 4.5. When I started using 4.5, I found
boot speed got extremely slow. Of course, I didn't care about it
(but I felt "NOT GOOD"), but the problem is after shutting down; After shutting
down, resuming from suspend, and/or rebooting, I found the system got "dead".
i.e. Pressing "Power" button, PC can boot up, but doesn't process uEFI boot
  process and doesn't show anything including "ASUS Logo".

## Why 4.4?
The latest version I confirmed it worked well is 4.4.

## Note when you use this pkgbuild
**Use this package on your responsibility.**

## License
See [LICENSE](LICENSE). It's **GPL2**. Note that this PKGBUILD is distributed
under **GPL2**, not **MIT**
