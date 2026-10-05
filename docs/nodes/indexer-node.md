# Run an askFinz node · Lend a machine to the index

Turn a Windows PC you already own into an askFinz indexer node — one line, no reformat, capped so it stays out of your way, easy to remove.

**Canonical page:** [https://askfinz.com/indexer_node](https://askfinz.com/indexer_node)

## Key points

### Every one of these was somebody's spare PC

No datacentre, no rack, no procurement. The figures below come straight from the fleet as it runs, and they move while you read them.

### Four jobs, none of them yours

Once it's running there is nothing to operate. The node takes work when the fleet has work, pauses when your machine is busy, and never asks you for anything.

### One line, then walk away

Open PowerShell as an administrator and paste the line below exactly as it is. Setup takes a few minutes and may ask for one restart the first time; run the same line again afterwards and it carries on where it stopped.

### Less than you'd think

An everyday desktop or laptop is enough. Each thing you add unlocks a little more of what the node can take on — but none of it is required to be useful.

### Find yourself on the live board

Every node in the fleet shows up on a public status page. Yours appears within a few minutes of install, under the name it was given.

### Five things people ask about

Most of these aren't faults at all. Nodes are built to recover on their own, so the usual answer is to give it a few minutes.

### Leaving is one line too

There is no notice period and nothing to negotiate. Run the removal line and the node hands back whatever it was working on, takes itself apart, and puts your settings back the way it found them.

### The rest of the picture

Indexer OS Have a spare PC or a Pi? Boot it into a dedicated appliance instead.

### It takes what you can spare, and nothing else

One line to start, one line to stop, nothing reformatted in between. It works within limits you set and steps back when you need the machine — the point is that you should be able to forget it is running.

## Frequently asked

### Will it slow my computer down?

It shouldn't. The node runs at the lowest priority on the machine, inside a sandbox with a hard ceiling on memory and processor time, so anything you do takes precedence. You can shut it down at any moment.

### Can it see my files or my browsing?

No. The node reads public pages from the web. It has no access to your documents, your browser, your accounts or anything else on the machine.

### Do I need to leave the PC on all the time?

No. A node that sleeps with the machine simply pauses. When the PC wakes, the node rejoins the fleet and keeps the same node number.

### Does it reformat or dual-boot anything?

No. This route installs alongside Windows and changes nothing about how the PC boots. If you want a machine to become a dedicated appliance instead, that is the Indexer OS route.

### How do I remove it?

One line, and the machine is returned to how it was. Your node number goes back into the pool for the next machine.

## Related

- [askFinz Indexer OS · The partner indexer appliance](https://askfinz.com/indexer_os)
- [askFinz Indexer for macOS: one line on Apple Silicon](https://askfinz.com/indexer_macos)
- [askFinz Indexer for Docker · One command, any OS](https://askfinz.com/indexer_docker)
- [Browser check — are you a real browser or a bot?](https://askfinz.com/browser_check)

---

Summary of [https://askfinz.com/indexer_node](https://askfinz.com/indexer_node), generated from the page itself. The page is the source of truth. Contact: hello@askfinz.com
