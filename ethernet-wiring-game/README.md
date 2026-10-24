# Ethernet Wiring Lab

An interactive, AI-assisted networking study project for Ankita Srivastava's IT portfolio. Practice T568A and T568B Ethernet wire order using an eight-pin RJ45 connector.

## Play

1. Open `index.html` in a browser and choose T568A or T568B.
2. Select a wire, then select a pin, or drag a wire onto a pin.
3. Fill all eight pins and select **Check wiring** for pin-by-pin feedback.
4. Correct mistakes or select **New round** to clear the connector and shuffle the tray.
5. Switch standards to practice both orders. Hints, a reference table, and **Show answer** are available.

Keyboard: Tab to a wire, press Enter or Space, Tab to a pin, and press Enter or Space. Select a filled pin with no wire selected to remove it. Selecting an already placed wire moves it; a wire cannot occupy two pins.

The session counter awards one perfect round per unassisted round. Hints, the reference table, and revealing the answer mark a round as assisted. Counts reset on page reload; no account or data collection is required.

## Pinout

View the plug with the gold contacts facing you, clip away, and cable pointing down. Pins run 1 to 8 from left to right.

| Pin | T568A | T568B |
| --- | --- | --- |
| 1 | White/green | White/orange |
| 2 | Green | Orange |
| 3 | White/orange | White/green |
| 4 | Blue | Blue |
| 5 | White/blue | White/blue |
| 6 | Orange | Green |
| 7 | White/brown | White/brown |
| 8 | Brown | Brown |

The game checks color order, not physical cable quality. Real cables require correct termination and testing.

## Run and host

No build step, dependencies, backend, or API keys. Download `index.html` and open it directly in a modern browser.

This folder can be served through GitHub Pages. If `html_portfolio` publishes the root of `main`, the game path is `/html_portfolio/ethernet-wiring-game/`. If Pages is not enabled, a repository administrator can enable it in **Settings → Pages → Deploy from a branch → main → /(root)**. Do not change an existing publishing configuration without checking it first.

## Project context and credits

Built with AI assistance as a personal study tool. The HTML, CSS, and JavaScript implementation was generated for this project. This repository does not claim independent authorship of AI-generated code or completion of physical cable testing.

Inspired by [Erivera3's Ethernet Wiring Practice Game](https://github.com/erivera3/ethernet-wiring-game). Original implementation and visual design for this version; no source code or personal memory method copied from the reference project.

Technical reference: [Fluke Networks: T568A vs T568B](https://www.flukenetworks.com/knowledge-base/application-or-standards-articles-copper/differences-between-wiring-codes-t568a-vs).

Unofficial study resource, not affiliated with CompTIA.
