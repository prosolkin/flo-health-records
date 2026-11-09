# Lab results in Flo: concept prototype

An interactive prototype for a take-home task: how a cycle-tracking app could bring clinical lab results in, show each result on the cycle day it was taken, and keep consent, privacy and revocation clear at every step.

**Open it:** https://prosolkin.github.io/flo-health-records/ (password in the submission email)

Add `?talk` to the URL for the presentation view: full-screen scenes over the prototype, with the live demo inside (→ next scene; ← back; Esc shows the prototype; F toggles the side panels during the demo). Backup scenes follow the close.

The page shows a phone on the left and, on the right, what happens behind each screen: the entry point, consent per purpose, the platform permission, import, the result in cycle context, a result outside the lab's range, a sensitive result, a guided walk-through, the proposed clinician hand-off, and pause, disconnect and delete.

This repository holds only the encrypted page (StatiCrypt, AES-256). Mock data and illustrative lab ranges only; nothing leaves the page.

Concept work by Alexander Prosolkin. Not affiliated with or endorsed by Flo Health.
