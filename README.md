# Solution for megabeets (ROP Chain)

This is my solution for part 2 of [A journey into Radare2](https://github.com/ITAYC0HEN/A-journey-into-Radare2). The corresponding blog post can be found [here](https://www.megabeets.net/a-journey-into-radare-2-part-2/).

The exploit works as follows:

- Leak the address of `puts`
- Build a ROP chain in order to spawn a shell.

Credits: [Itay Cohen](https://github.com/ITAYC0HEN)
