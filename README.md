# <img src='https://github.com/user-attachments/assets/3701cadf-f646-45d5-99ed-bb742a3afe20' width='24' /> Adept Anyball

[Ploopy Adept](https://ploopy.co/adept-trackball) mod for 8 mm BOSCH Rexroth <a href='#btus-needed'>BTUs</a> with optional <a href='#magnets'>magnetically</a> attachable buttons. \
Various adapters are available, making it possible to use not just BTUs but also default ball bearings, static bearings. 

<img src='https://github.com/user-attachments/assets/2b93e8b8-df7b-4a21-967f-d1aeba64710c' width='640' />

## Compatibility<sup>\*</sup>

| Ball                |     |                                                                                                                             |
| ------------------- | --- | --------------------------------------------------------------------------------------------------------------------------- |
| 34 mm, 38.1 mm      | ✔️  | e.g. Perixx, original Ploopy Nano ball; see [this repo](https://github.com/adept-anyball/ploopy-adept-small-btu)            |
| 44 mm               | ✔️  | e.g. from ProtoArc, JOMAA                                                                                                   |
| 45 mm               | ✔️  | default Adept ball                                                                                                          |
| 50.8 mm             | ✔️  | english pool ball, from Adesso T50                                                                                          |
| 52.4 mm             | ✔️  | snooker ball                                                                                                                |
| 55 mm               | ✔️  | e.g. from Kensington Expert, Perixx                                                                                         |
| 57 mm               | ✔️  | pool ball                                                                                                                   |
| 60 mm               | ✔️  | pool ball                                                                                                                   |
| 68 mm <sub>?!</sub> | ✔️  | russian<sup>\*\*</sup> pyramid ball                                                                                         |

<sup>\*chances are your ball is compatible if it's within the \[min, max\] range, and it probably is.</sup> \
<sup>\*\*kindly consider [supporting Ukraine](https://u24.gov.ua) to fight Russia in the ongoing invasion and occupation.

## General tips

> ❗️ **Important!** \
> \
> Use STL (not STEP) files for Slic3r forks, i.e. Prusa-, Orca-, Bambu Slicer. 
> STEPs are for CADs. There has been many cases reported when a STEP file has caused invalid geometry, 
> including critical changes such as "no gap between button and shell".

### Printing

1. There MUST be no supports, unless you really know what you are doing.

2. PLA, PETG, ABS — any of those are fine. 

### Other

1. Insert magnets on a flat hard surface while the device is not assembled.

2. Cyanoacrylate (superglue) works nice for magnets.

3. If you experience buttons sticking, try loosening the screws or removing the sensor cover.

4. If you experience bad tracking, you may want to print and install spacers.

## 57-68 mm ball (or 50-60 mm with spacers installed)

<p>
  <img src='https://github.com/user-attachments/assets/40e2a5de-36f0-48e6-8912-0989d2262f93' width='300' float='left'>
  <img src='https://github.com/user-attachments/assets/b444aa28-2a66-43e9-b1cf-f955b70abfa2' width='420' float='right' />
</p>

## 50-55 mm ball

Also available for non-standard BTUs: 
[SP-8](https://github.com/adept-anyball/mod/issues/5), [Veichu-15](https://github.com/adept-anyball/mod/issues/11).

> If you use CY-8H Aliexpress BTUs, it is recommended to go with the 50-52.4mm version instead. \
> You can ignore the fact that it is deprecated in such a case. \
> That version (in combination with this BTUs) should work with a 55 mm ball too.

<p>
  <img alt='55mm ball' src='https://github.com/user-attachments/assets/d80c5e04-c924-448d-8d6a-b7765a459fc6' width='450'/>
  <img alt='55mm ball' src='https://github.com/user-attachments/assets/a63dc1f1-9e36-4008-807e-f848684f6cfa' width='325'/>
</p>

## 50-55 mm ball (short version)

Fits a 50-55 mm ball. In this mod, the bottom and top parts of the original Adept case have been modified.

<p>
  <img alt='55mm short top' src='https://github.com/user-attachments/assets/db33e8f8-9daf-4204-a075-6289842b20d8' height="320px" float="left"/>
  <img alt='55mm short side' src='https://github.com/user-attachments/assets/5ff035ff-ad81-41ec-9ad9-e9e4072ffbf9' height="320px" float="right"/>
</p>

## 50-55mm ball (short, thin bezel)  
Fits a 50-55 mm ball. In this mod, the bottom and top parts of the original Adept case have been modified.  
It was built based on the short version above.
<div style="display: flex; justify-content: space-between; align-items: center;">
  <img src="https://github.com/Dexter-KBD/mod/blob/7e5c20a7d53ba57e26f54449fc6a730474b02995/50-55mm%20Ball%20(Thinner%20Bezel)/Image/50-55mm-Ball-_Thinner-Bezel_2.jpg?raw=true" alt="Side View" height="300px">
  <img src="https://github.com/Dexter-KBD/mod/blob/7e5c20a7d53ba57e26f54449fc6a730474b02995/50-55mm%20Ball%20(Thinner%20Bezel)/Image/50-55mm-Ball-_Thinner-Bezel_3.jpg?raw=true" alt="Close-up View" height="300px">
</div>

## 44-45 mm ball

This mod fits the original 45mm ball. \
You can find the 3MF files for Bambu printers on [Makerworld](https://makerworld.com/en/models/1087275#profileId-1080219).

<p>
  <img alt='45mm top' src='https://github.com/user-attachments/assets/2589164e-46c9-49c7-900f-104ad5a5d75e' height="300px" float="left"/>
  <img alt='45mm top without ball'  src='https://github.com/user-attachments/assets/8be3af2c-b452-402b-9e61-42fa9efe3d8d' height="300px" />
</p>

## 50-52.4 mm ball _DEPRECATED_

> The shell is deprecated, see 50-55mm one. It has standard size buttons and better BTUs placement.

<p>
  <img src='https://github.com/user-attachments/assets/e669314c-c8d0-4c04-aaf5-805082c13203' width='300' float='left' />
  <img src='https://github.com/user-attachments/assets/baf4e37a-e5a8-46d3-9f48-b12d4a77d95e' width='420' float='right' />
</p>

## BTUs needed

[This is the link](https://store.boschrexroth.com/BALL-TRANSFER-UNIT_R053010810) to genuine BOSCH Rexroth BTUs.  
Also available on [efog.tech](https://efog.tech/products/bosch-rexroth-btu). 

<p>
  <img alt='BTU specsheet' src='https://github.com/user-attachments/assets/a1a8a0e0-8605-44d5-94d4-03515e37f13b' height='250' width='auto' />
</p>

[EFOG.TECH® BTUs](https://efog.tech/products/efogtech-btu) are fully compatible.  
CY-8H BTUs from AliExpress [are compatible](https://github.com/adept-anyball/mod/issues/6), with one exception so far. \
[SP-8](https://github.com/adept-anyball/mod/issues/5) and [Veichu-15](https://github.com/adept-anyball/mod/issues/11) are not directly compatible, but there are model(s) available. \
Rexroth BTUs are clearly superior and are highly recommended.

## Magnets

You will need 4x2 mm circular neodymium magnets, full set (device + buttons) is 24pcs. \
They MUST be glued, ideally with a cyanocrylate based glue. 

## Quality Assurance

We have the best of the best.

![20250218_104146](https://github.com/user-attachments/assets/fa81e27c-0c66-4a6d-b77f-7f7ac985f64e)

## Even more photos

See [gallery](https://github.com/adept-anyball/mod/issues/7).
