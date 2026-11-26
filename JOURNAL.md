---
title: "NFC Business Card"
github: "https://github.com/SuhaniSharma072/NFC-Business-Card/tree/main"
description: "This is a PCB NFC Business Card and  it can transmit a URL on tap and light up. I am building this as this is my first PCB ever and because this is a beginner project."
created_at: "2026-11-24"
total_time: "2h 36m"
---

# November 25, 2026: Finished The Schematic

<img width="876" height="780" alt="image" src="https://fabricate.hackclub-assets.com/a79bd65691292a8f3c8245cb51729b83e3f968851bf5a548e42af5a264395995/image-png/b41a8775-379b-43e6-be19-313d8531a37c.png" />

# November 25, 2026: PCB Layout and Routing for the NFC Business Card


<img width="437" height="611" alt="image" src="https://fabricate.hackclub-assets.com/0fc4895bed6d08ea423f3f4fd10e1d20328ba80943237b63cacd5c545ae8205e/image-png/ebb4db99-f716-4211-ab25-11641ee7cc77.png" />

# November 25, 2026: Adding a QR Code and Custom Silkscreen Art


<img width="870" height="636" alt="image" src="https://github.com/user-attachments/assets/c66e9ace-ccd8-48e1-b15a-35716a483483" />

# November 24, 2026: Finished The Schematic
<!-- fabricate:entry 3873 -->

I placed the NT3H2111 NFC chip and connected its LA and LB pins to a 25×48 mm NFC antenna. I tied VOUT to VCC. I added a 220 nF capacitor between VOUT and ground. Then I wired a 47 Ω resistor and an LED in series from VOUT to ground.

![](https://fabricate.hackclub-assets.com/833eadef698592ee9d2ea77d413e831bcaafed462331f43969d4ca25ebff5d16/image-png/Screenshot%202026-11-24%20at%2010.25.44%E2%80%AFPM.png)

**Total time spent: 24m**

# November 25, 2026: PCB Layout and Routing for the NFC Business Card
<!-- fabricate:entry 3925 -->

I moved to the PCB layout and positioned the NFC antenna coil flat on the board. I connected U1's antenna pin to the coil's outer pad with a trace on the top layer. The auto-router connected U1 to the coil's inner end with a trace on the bottom layer. I routed the power connection from C1 to U1 and R1 by using two vias and a bottom-layer trace to jump under other traces. I gave the vias and traces the correct net name so they would connect. I found and fixed two tiny gaps where traces didn't quite touch their pads. All 8 nets are now fully connected. I ran a design rule check, and the remaining errors come from the antenna coil touching its own ends.

![](https://fabricate.hackclub-assets.com/0c7d00e07c43ab716756f022d75c252ff79ed0dff9a7a68f320f205150a73090/image-png/image.png)

**Total time spent: 2h**

# November 25, 2026 (entry 2): Adding a QR Code and Custom Silkscreen Art
<!-- fabricate:entry 3927 -->

I added a QR code to the bottom-left corner of the card on the silkscreen layer. The QR code links to my portfolio. I added the text "Scan to see my Portfolio" with an arrow pointing to it. I added a small teddy bear design in the top-right corner. I previewed the finished board in 3D with a dark blue color.

![](https://fabricate.hackclub-assets.com/24458ad4c9c37a4284f38df1968ce80e65bf5b1d2a953746c4e5cbac16656ca1/image-png/image.png)

**Total time spent: 12m**
