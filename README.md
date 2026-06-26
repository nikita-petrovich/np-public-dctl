# DCTLs for DaVinci Resolve

A collection of simple, conceptual DCTLs that turned out interesting enough to share with the world.  
No overengineering — just practical, creative tools.

> [!NOTE]
>
> I only sell my DCTLs through [**aescripts**](https://aescripts.com/authors/m-p/nikita-petrovich/) – no other marketplaces or direct sales.

**System Requirements:** 
* DaVinci Resolve Studio 19.1 and newer;
* GPU: NVIDIA or Apple Silicon. Not tested on other systems.

---

### Lazy Bleach

Creates a Bleach Bypass-like look by finding an average color of the current frame and applying it on top of the source image using a custom blend mode.

> [!CAUTION]
> 
> Unusable on a low-end PC.
> 
> Almost unusable on timelines larger than 4K.
> 
> Lower the quality value very carefully!

[Learn more in the video](https://www.youtube.com/watch?v=gM-Ja1gioj4)

---

### Lazy Blur

Blurs per pixel in random directions. Perfect for filmic softness, glass blur effects, or stylising graphics. Works great with Lazy Grain DCTL.

[Learn more in the video](https://www.youtube.com/watch?v=oz4jkEMOCYg)

---

### Lazy Grain

Adds film grain by applying random Lift, Gamma, Gain, Offset, and subtractive saturation **per pixel**.  
No noise textures, no scanned film analysis — just lazy randomness.

[Learn more in the video](https://youtu.be/EV1LnvAtIL4)

---

### Saturation RGB

DaVinci Resolve’s native HSV saturation looks great, until it destroys your shadows.  
This custom RGB‑based DCTL gives you clean, artifact‑free saturation.

**Includes 7 modes:**  
- Subtractive  
- Standard  
- Additive  
- Middle‑base  
- Channel‑specific (R, G, B)  

[Learn more in the video](https://youtu.be/gx2KwL1FD7Y)

---

## 🔌 My OpenFX Plugin Concepts

- [**QRCoder**](https://github.com/nikita-petrovich/OFX-QRCoder) – Generate QR codes directly inside DaVinci Resolve or any OpenFX host.  
- [**Nikita Blend Mode**](https://github.com/nikita-petrovich/nikita-blend-mode) – An original composite mode (`a + luma(a) − b`) that could be used to create a unique bleach‑bypass style effect.

---

## 📁 Installation

- If this is your first DCTL, simply drag the .dctl file into your Resolve LUT folder, then restart DaVinci to see it in the list of DCTLs in OpenFX.
- To locate the LUT folder in your system, open DaVinci Resolve - go to Color Page - open LUTs tab - right click on the LUTs folder - reveal in Finder (on MacOS) or its equivalent in Windows and Linux.

---

## Support future updates & ideas

If you find these tools useful, consider grabbing my other DCTLs on 👉 [**aescripts**](https://aescripts.com/authors/m-p/nikita-petrovich/)

You can also support me with cryptocurrency:
- BTC: bc1q44j8e4nws4mjfzgnmajgewcek6ss5q28glfsn2
- ETH/USDT/USDC (ERC20): 0x740D1d2fc9DD4E34A3deef142AB53331DC73EAe2
- USDT/USDC (TRC20): TKRYcJsG1Y1yg2zFAarxnW8u81RzMTTcAj
