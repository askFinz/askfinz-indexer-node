# askFinz Indexer for macOS: one line on Apple Silicon

Run an askFinz indexer node on an Apple Silicon Mac. One line in Terminal, signed in from the browser, and the Mac's graphics chip does the heavy work. Built natively for M1 and later.

**Canonical page:** [https://askfinz.com/indexer_macos](https://askfinz.com/indexer_macos)

## Key points

### Every one of these is somebody's spare machine

No datacentre, no rack, no procurement — just capacity people were not using. The figures below come straight from the fleet as it runs, and they move while you read them.

### Four jobs, none of them yours

Once it is running there is nothing to operate. It takes work when the fleet has work, stands back when you are using the Mac, and never asks you for anything.

### One line, then walk away

Open Terminal — press Command and Space, type Terminal, press Return — then paste the line below. It opens your browser to approve the Mac, then sets itself up and starts reading.

### An Apple Silicon Mac, and a plug

If the Mac has an M-series chip, it can run a node. Each thing below raises how much it takes on — but a base M1 with 8 GB is a real contributor, not a token one.

### A laptop is the only node that closes

Every other machine in the fleet is a desktop, a server or a container — none of them fold shut. A Mac laptop does, and a sleeping node is simply an absent one: it stops mid-page and the work goes back to the fleet.

### Find yourself on the live board

Every node in the fleet shows up on a public status page. Your Mac appears within a few minutes, under the name it was given.

### Five things people ask about

Most of these aren't faults at all. Nodes are built to recover on their own, so the usual answer is to give it a few minutes.

### Leaving is one line too

No notice period, nothing to negotiate. It hands back whatever it was working on, releases its number to the pool, removes its two background services, and puts your sleep settings back the way they were.

### Four routes, one fleet

Indexer OS Dedicate a spare PC. A custom Linux OS that boots straight into a node.

### The chip is already there. Put it to work

A node built natively for Apple Silicon, so the graphics cores do the reading rather than sitting idle — measured at around six times what the processor manages alone.

## Frequently asked

### Which Macs does this work on?

Any Mac with Apple Silicon — M1, M2, M3, M4 and later, in any model. The node is compiled natively for that chip, so nothing runs under emulation. Intel Macs are not covered by this route, but they can still run a node through Docker.

### Will it slow the Mac down?

It shouldn't. It runs at low priority with a fixed ceiling on how much it takes, and it sizes itself to the machine when it installs. Anything you are doing takes precedence. You can stop it at any moment.

### Can it see my files?

No. It reads public pages from the web. It has no access to your documents, your photos, your browser, or anything you are signed into.

### Do I need to paste a key or a secret?

No. The line opens your browser and asks you to approve a short code, the same way signing in to a developer tool works. Nothing is typed in and nothing is stored in your shell history.

### Why does it stop my Mac sleeping?

A sleeping node is an absent node — it stops reading and the work goes back to the fleet. The installer disables sleep only while the Mac is on mains power, and only for the machine, not the display. Battery behaviour is untouched.

### How do I remove it?

One line, the same way it went on. It hands back whatever it was working on, removes its two background services, restores your original sleep settings, and releases its node number to the pool.

## Related

- [Run an askFinz node · Lend a machine to the index](https://askfinz.com/indexer_node)
- [askFinz Indexer OS · The partner indexer appliance](https://askfinz.com/indexer_os)
- [askFinz Indexer for Docker · One command, any OS](https://askfinz.com/indexer_docker)
- [Browser check — are you a real browser or a bot?](https://askfinz.com/browser_check)

---

Summary of [https://askfinz.com/indexer_macos](https://askfinz.com/indexer_macos), generated from the page itself. The page is the source of truth. Contact: hello@askfinz.com
