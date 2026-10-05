# askFinz Indexer for Docker · One command, any OS

Run an askFinz indexer node as a Docker container on Windows, Linux or macOS. One command to start, one to remove, capped so it stays out of your way.

**Canonical page:** [https://askfinz.com/indexer_docker](https://askfinz.com/indexer_docker)

## Key points

### Every one of these is a container on someone's machine

No datacentre, no rack, no procurement — just spare capacity, wrapped in a container. The figures below come straight from the fleet as it runs, and they move while you read them.

### Four jobs, none of them yours

Once it's running there is nothing to operate. It takes work when the fleet has work, pauses when the host is busy, and never asks you for anything.

### One command, then walk away

With Docker running, paste the line below into a terminal. On Windows use a WSL, Git Bash or Docker Desktop shell.

### Docker, and not much else

If a machine already runs Docker, it can run a node. Each thing you add unlocks a little more of what the container can take on — but none of it is required to be useful.

### Find yourself on the live board

Every node in the fleet shows up on a public status page. Your container appears within a few minutes, under the name it was given.

### Five things people ask about

Most of these aren't faults at all. Nodes are built to recover on their own, so the usual answer is to give it a few minutes.

### Leaving is one command too

No notice period, nothing to negotiate. Remove the container and the node hands back whatever it was working on and releases its number to the pool.

### Three routes, one fleet

Indexer OS Dedicate a spare PC. A custom Linux OS that boots straight into a node.

### One command to start. One to remove

It runs anywhere Docker does — Windows, Linux or macOS — capped so it sits alongside whatever else the host is doing rather than competing with it. Nothing is installed outside the container, so taking it off leaves the machine exactly as it was.

## Frequently asked

### Which operating systems does this work on?

Any host that runs Docker: Linux (Docker Engine), macOS and Windows (Docker Desktop, which uses WSL2). The same one-line command works on all of them — on Windows run it from a WSL, Git Bash or Docker Desktop terminal.

### Will it slow the machine down?

It shouldn't. The container runs with a hard ceiling on memory and CPU and at low priority, so anything else on the host takes precedence. You can stop it at any moment.

### Can it see my files?

No. It runs isolated in its own container and reads public pages from the web. It has no access to the host's files, browser or accounts beyond what the container is given.

### How do I share a GPU?

Install the NVIDIA container toolkit on the host and re-run the command — the installer detects it and passes the card through so the node can join the shared embedding pool.

### How do I remove it?

One command — `docker rm -f askfinz-indexer` — stops and deletes the container. It hands back its work first, and its node number returns to the pool. Nothing is left on the host.

## Related

- [Run an askFinz node · Lend a machine to the index](https://askfinz.com/indexer_node)
- [askFinz Indexer OS · The partner indexer appliance](https://askfinz.com/indexer_os)
- [askFinz Indexer for macOS: one line on Apple Silicon](https://askfinz.com/indexer_macos)
- [Browser check — are you a real browser or a bot?](https://askfinz.com/browser_check)

---

Summary of [https://askfinz.com/indexer_docker](https://askfinz.com/indexer_docker), generated from the page itself. The page is the source of truth. Contact: hello@askfinz.com
