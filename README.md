# tinyfpga-b2-first-project

My first project based on TinyFPGA B2. It simply blinks with an LED connected to
the pin 13.

Please note that beside of IceStorm you have to install the tinyfpgab script:

```
sudo pip2 install tinyfpgab
```

**Hint:** After pulling the board out of PC and plugging it back you need to
execute `tinyfpgab -b` once or twice to load the last configuration. When
plugging the board into a power bank the last configuration will be loaded
automatically.

Recommended tutorials:

* [Open FPGA Verilog Tutoral][t1]
* [Go Board Tutorials][t2]


[t1]: https://github.com/Obijuan/open-fpga-verilog-tutorial/wiki
[t2]: https://www.nandland.com/goboard/index.html
