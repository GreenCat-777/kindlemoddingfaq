---
title: Disabling Crash Logs
type: docs
prev: docs/Database/
---

You might see `KPPMainApp` or `Mesquite` files pop-up they're annoying here's how to stop them.

## Scriptlet
1. [Download](https://gc-wiki.vercel.app/downloads/crash.sh)

## With a PC
1. Connect the Kindle to a PC.
2. Create a file called `DISABLE_CORE_DUMP` with no file extension.
3. Copy `DISABLE_CORE_DUMP` to the kindle's root directory.

## KTerm
1. Open KTerm
2. Run the command `touch /mnt/us/DISABLE_CORE_DUMP`
