<p align="center"><img src="title.svg" alt="K-FSW"></p>


<p align="center">
  <img src="https://raw.githubusercontent.com/dgonzalez97/k-fsw/develop/docs/media/multi-board-can.gif" alt="A ground station talking to three boards over CAN and radio" width="90%">
</p>

I'm David, an embedded developer, and [K-FSW](https://github.com/dgonzalez97/k-fsw) is the modular and open source flight software I'm building for small satellites (the K comes from [Koala](https://friendsofthekoala.org/about-koalas/)).

It runs on [Zephyr](https://www.zephyrproject.org/) and is split into five small repositories: board support,
communications, services (parameters, file transfer, device, firmware update, housekeeping, events, file based operations), a ground station using [YAMCS](https://yamcs.org/), and modules, the only part a specific mission should create, allowing this to run in OBCs, radios or any payload. Any module can be easily configured to match the subsystem requirements

Nodes use [CSP](https://github.com/libcsp/libcsp), a protocol for [CubeSats](https://en.wikipedia.org/wiki/CubeSat), the protocol can be changed since k-fsw is modular.
It's a personal project, but it runs on real hardware and every
change goes through CI/CD.

Contact me if you have any questions: <a href="mailto:dgonzalez97@gmail.com"><img src="email.svg" height="16" alt="Email"></a> [dgonzalez97@gmail.com](mailto:dgonzalez97@gmail.com)

<a href="https://github.com/dgonzalez97/k-fsw"><img src="k-fsw-badge.svg" alt="K-FSW on GitHub" align="left"></a><a href="https://www.linkedin.com/in/david-gonzalezf/"><img src="linkedin.svg" width="64" alt="LinkedIn" hspace="35"></a><br><a href="https://x.com/ddgonzalez97"><img src="x.svg" width="64" alt="X" hspace="35"></a><br clear="left">
