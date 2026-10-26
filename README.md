<a href="https://qadan.co/work/" aria-label="Case studies at qadan.co/work">
<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/hero-mobile-dark.png">
  <source media="(max-width: 600px)" srcset="assets/hero-mobile-light.png">
  <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.png">
  <img src="assets/hero-light.png" alt="Moe Qadan, independent senior UX and frontend engineer, with the line: I do UX and frontend as one job." width="880">
</picture>
</a>

I do UX and frontend as one job. Most of the work I take on is repair: a platform that grew without a system, a site that ranks well and converts badly, a frontend that ships fine on Chrome and falls apart on iOS. Greenfield happens, but most of my work isn't that.

I designed and built CarSpotter, VINly, and ChatOBD2. Two open-source libraries came out of the same automotive work. I currently lead the web experience at MagTek.

Now: VINly is live on the App Store. ChatOBD2 is in QA and field testing.

<img src="assets/q-cut.svg" width="24" height="8" alt="">

## Independent products

### CarSpotter

<sub>Independent product · iOS · On the App Store</sub>

<p align="center">
  <a href="https://qadan.co/work/car-spotter/"><img src="assets/project-carspotter.jpg" alt="CarSpotter poster: the Saturn identity, a daily car question, and the matching reveal." width="720"></a>
</p>

Five cars a day, four choices, then the whole car and a fact. I designed the game and the iPhone app, built the Saturn-led identity, and wrote the ImageMagick pipeline that prepares the photography.

[App Store](https://apps.apple.com/app/carspotter-daily-car-game/id6777868215) · [carspottergame.com](https://carspottergame.com) · [Case study](https://qadan.co/work/car-spotter/)

### VINly

<sub>Independent product · iOS · On the App Store</sub>

<p align="center">
  <a href="https://qadan.co/work/vinly/"><img src="assets/project-vinly.jpg" alt="VINly poster: a 2024 Ford F-150 public-record report and the on-device VIN reader." width="720"></a>
</p>

Scan a VIN and get the car's public record: recalls, complaints, crash tests, fuel cost, and listings nearby. The VIN is read on the phone, validated against the ISO 3779 check digit before any lookup, and the photo never leaves the device. Free.

[App Store](https://apps.apple.com/us/app/vinly-buyer-reports/id6774041303) · [vinly.dev](https://vinly.dev) · [Case study](https://qadan.co/work/vinly/)

### ChatOBD2

<sub>Independent product · iOS · In QA and field testing</sub>

<p align="center">
  <a href="https://qadan.co/work/chatobd2/"><img src="assets/project-chatobd2.jpg" alt="ChatOBD2 poster: a diagnostic chat and verdict surface on a 2010 Toyota Prius." width="720"></a>
</p>

ChatOBD2 turns an OBD2 scan into ranked, plain-language causes. A deterministic reasoning engine correlates codes, freeze-frame data, and fuel trims; six reasoning layers and a 38,000-token prompt budget sit before the model call, and the report is schema-validated before the app renders it. The app, marketing site, and developer portal are built. In QA and field testing.

[Case study](https://qadan.co/work/chatobd2/)

<img src="assets/q-cut.svg" width="24" height="8" alt="">

## Open source

<p align="center">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/shelf-open-source-mobile-dark.jpg">
    <source media="(max-width: 600px)" srcset="assets/shelf-open-source-mobile-light.jpg">
    <source media="(prefers-color-scheme: dark)" srcset="assets/shelf-open-source-dark.jpg">
    <img src="assets/shelf-open-source-light.jpg" alt="elmulator and vinplain project posters." width="880">
  </picture>
</p>

### elmulator

<sub>Open source · Swift + Python · MIT</sub>

The iOS Simulator has no radio, and Apple does not let you mock a peripheral, so the Bluetooth layer usually goes untested. elmulator is a scripted ELM327 you can point real CoreBluetooth code at, in CI, with no car and no adapter. A conformance suite keeps the Swift and Python servers byte-identical. Zero runtime dependencies; seven fixture scenarios.

[Repository](https://github.com/qadanm/elmulator) · [PyPI](https://pypi.org/project/elmulator/) · [Swift Package Index](https://swiftpackageindex.com/qadanm/elmulator) · [Case study](https://qadan.co/work/elmulator/)

### vinplain

<sub>Open source · TypeScript · npm</sub>

Reads the public record for a VIN: factory decode, NHTSA recalls and complaints, crash ratings, and EPA fuel economy. Three public data sources, zero runtime dependencies, 34 tests. MIT.

[npm](https://www.npmjs.com/package/vinplain) · [Website](https://qadanm.github.io/vinplain/) · [Repository](https://github.com/qadanm/vinplain) · [Case study](https://qadan.co/work/vinplain/)

<img src="assets/q-cut.svg" width="24" height="8" alt="">

## Platform work

<p align="center">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/shelf-platform-mobile-dark.jpg">
    <source media="(max-width: 600px)" srcset="assets/shelf-platform-mobile-light.jpg">
    <source media="(prefers-color-scheme: dark)" srcset="assets/shelf-platform-dark.jpg">
    <img src="assets/shelf-platform-light.jpg" alt="MagTek Platform and Advisor Platforms project posters." width="880">
  </picture>
</p>

### MagTek Platform

<sub>Platform work · Current</sub>

Platform context: eleven sites on one ASP.NET MVC codebase, $11B processed annually, 99.9% uptime. My contribution: about 85% frontend ownership, a Razor component library past 100 pieces, a CSS foundation rebuilt as tokens, and migrations sequenced so production stays up.

[Case study](https://qadan.co/work/magtek-platform/)

### Advisor Platforms

<sub>Platform work · Earlier</sub>

Advisor and customer portals for more than fifty wealth and banking institutions ran on one multi-tenant framework at InvestCloud, each with its own branding and density. I implemented the frontends and translated the designs, contributed to or led 0-to-production deploys.

[Case study](https://qadan.co/work/financial-platforms/)

<img src="assets/q-cut.svg" width="24" height="8" alt="">

## Tools

Most new work is TypeScript and React. MagTek is C# and Razor; the automotive work is Swift and Python. The current toolchain is on [Uses](https://qadan.co/uses/).

## Contact

[qadan.co](https://qadan.co/) · [Work](https://qadan.co/work/) · [LinkedIn](https://linkedin.com/in/mqadan) · [GitHub](https://github.com/qadanm) · [moe@qadan.co](mailto:moe@qadan.co)
