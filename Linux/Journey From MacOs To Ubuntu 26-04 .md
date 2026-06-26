# From macOS to Ubuntu 26.04 LTS: Giving My 2017 MacBook Air a Second Life

> *Sometimes the best upgrade isn't buying a new laptop. It's changing the operating system.*

## Why I Left macOS

I own a **MacBook Air 2017**.

For years it served me well. It survived college assignments, random coding experiments, hundreds of Chrome tabs, and way too many late-night YouTube sessions. But over time something changed.

Every macOS update felt heavier.
The laptop wasn't getting slower because the hardware suddenly became bad—it was just getting older while the software kept demanding more.

I also had another reason.

I wanted to get serious about **Cybersecurity**.

And although macOS is an amazing operating system, I knew almost every guide, lab, CTF walkthrough, networking tutorial and penetration testing course assumed Linux.

Instead of buying another laptop, I decided to give this machine another life.

That decision turned into one of the most fun projects I've done.

---

# The Beginning

I didn't dual boot.

I didn't keep a backup partition.

I wiped macOS completely.

There was something exciting about committing to Linux with no easy way back.

I downloaded **Ubuntu 26.04 LTS**, flashed it onto a USB drive and installed it.

The installation itself was surprisingly easy.

The first boot wasn't.

---

# The Reality After Installation

The desktop looked clean.

Everything looked modern.

Then I started actually using it.

That's when the adventure really started.

Almost immediately I discovered things that weren't working exactly how I expected.

* Wi-Fi behaved strangely.
* Audio wasn't right.
* Some hardware on Apple's Broadwell machines needed extra attention.
* Ubuntu looked... well... like Ubuntu.

I came from macOS.

Years of muscle memory don't disappear overnight.

---

# Learning Linux Instead of Copying Commands

One promise I made to myself:

I didn't want to become someone who copies terminal commands from random websites without understanding them.

So instead of asking,

> "Give me the fix."

I kept asking,

> "Why does this happen?"

That changed everything.

Instead of only solving problems, I started understanding Linux.

I learned how package managers work.

How repositories work.

Why `apt update` is different from `apt upgrade`.

What Snap packages are.

What Flatpaks are.

How repositories are stored.

How Linux resolves software.

Things that looked scary a week ago slowly became normal.

---

# The Terminal Slowly Became My Friend

At first every command felt dangerous.

Especially this one:

```bash
rm -rf
```

Everyone jokes about it.

Then I finally understood what it actually means.

* `rm` → remove
* `-r` → recursive
* `-f` → force

Not scary anymore.

Just powerful.

The terminal slowly changed from something I feared into something I actually enjoyed using.

---

# Making Ubuntu Feel Like Home

I didn't want Ubuntu to feel like a replacement.

I wanted it to feel like *my* computer.

So I spent time customizing it.

I changed:

* Fonts
* Dock
* Super Key behavior
* Desktop appearance kept Ubuntu like

The goal wasn't to clone macOS perfectly.

It was to keep the things I loved while enjoying everything Linux offers.

Now when I open the lid, it still feels familiar—but much faster, Best of the both world Ig.

---

# Building My Workspace

Once the operating system felt right, I started installing the tools I actually wanted.

## Development

* VS Code
* Brave Browser

## Documentation

* Obsidian

This became my second brain.

Every command.

Every mistake.

Every lesson.

Everything goes into notes now.

## Virtualization

VirtualBox became the heart of my future cybersecurity lab.

Instead of risking my main operating system, I can create isolated environments and break things safely.

Which is honestly the best way to learn.

---

# Wireshark Was the First "Wow" Moment

Installing Wireshark was one thing.

Actually opening it was another.

Watching packets move across the network in real time felt like pulling back the curtain on the internet.

You suddenly realize...

Your computer is talking all the time.

There's so much happening underneath the surface.

That was probably the first moment where cybersecurity stopped being "videos on YouTube" and started feeling real.

---

# Small Problems That Taught Big Lessons

Not every lesson came from installing software.

Sometimes the mistakes were even more valuable.

I learned why:

```bash
cp
```

failed.

Why directories can't always be removed with:

```bash
rm
```

and sometimes require:

```bash
rm -rf
```

I accidentally collected broken repositories.

`apt update` started throwing errors.

Instead of ignoring them, I learned how Linux stores repository files inside:

```
/etc/apt/sources.list.d/
```

I found outdated repositories.

Removed broken ones.

Fixed package sources.

And eventually reached the most satisfying screen in Linux:

A clean

```bash
sudo apt update
```

with zero errors.

It felt ridiculously rewarding.

---

# Discovering That Linux Is Honest

One thing I genuinely appreciate about Linux:

When something breaks...

...it usually tells you *why*.

Maybe not in beginner language.

But the answer is almost always there.

The terminal isn't trying to hide anything.

You just have to learn how to read it.

---

# Why Ubuntu?

Ubuntu gives me:

* Long Term Support
* Huge documentation
* Massive community
* Excellent hardware support
* Stable package ecosystem

For someone building a cybersecurity workstation, that's a great place to start.

Kali belongs inside a virtual machine.

Ubuntu is my workstation.

---

# The Biggest Surprise

Performance.

This old MacBook Air feels alive again.

Applications launch faster.

Memory usage is lower.

The fan barely spins compared to before.

Battery life is still respectable.

For a laptop from 2017...

That's impressive.

---

# What I Learned

Switching operating systems wasn't really about Linux.

It was about becoming curious again.

Instead of clicking buttons...

I started understanding computers.

Instead of fearing the terminal...

I started using it daily.

Instead of memorizing commands...

I learned what they actually do.

Every error message became another lesson.

Every fix made me a little more confident.

---

# What's Next

This laptop is now becoming my dedicated cybersecurity machine.

The plan is to build everything from scratch.

* Networking fundamentals
* Linux administration
* Virtual labs
* Web security
* CTFs
* Reverse engineering
* Scripting
* Penetration testing
* Home lab

And I'll document all of it here on GitHub.

Not because I'm an expert.

Quite the opposite.

Because I want this repository to become a record of learning in public.

The mistakes stay.

The failed commands stay.

The debugging stays.

That's where the real learning happens.

---

# Final Thoughts

If you have an old laptop sitting in a drawer...

Don't throw it away.

Install Linux.

You might discover that the machine wasn't old.

It was just waiting for software that respected its hardware.

For me, this wasn't just switching from macOS to Ubuntu.

It was the moment I stopped being someone who simply *uses* a computer...

and started becoming someone who actually understands one.

And honestly...

I think this is just the beginning.




