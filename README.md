# OurMoney

A single-file, offline-first wedding budget and guest tracker. Hebrew, RTL,
no build step and no dependencies.

Tracks what you have paid and what is left, who is coming, and what each guest
gave — including each guest's gift measured against what their seats cost.

This repository holds the application only. It ships with no data: on first run
it asks you to import a JSON backup, and it can optionally sync between devices
through your own Supabase project. Guest lists and financial figures live
outside the repo by design.
