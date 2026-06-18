---
layout: post
title: "Nine Years of WAN Infrastructure Taught Me More About Security Than I Realized"
date: 2026-06-18
---

I spent nine years managing wide area network infrastructure, most recently as a WAN Services Manager
overseeing a large fleet of SD-WAN edge devices across financial institution customer sites. I handled
circuit failover, edge device configuration, performance monitoring, and the kind of 2 a.m. calls that
remind you exactly how much depends on the network staying up.

I never thought of myself as a security professional.

Then I started studying for the Cisco SCOR 350-701 exam, and something clicked about three days in:
I had already been doing security work for nine years. I just hadn't been calling it that.

## What WAN management looks like through a security lens

When you manage WAN infrastructure for financial institutions, security isn't a feature you configure
once and forget. It's baked into every decision.

Every SD-WAN edge device I managed was a potential entry point. Every circuit failover was a moment
when traffic behavior changed and visibility mattered. Every time a branch couldn't reach the core,
I was triaging whether it was a routing problem, a hardware failure, or something worse. The discipline
of keeping dozens of edge devices updated, segmented, and monitored across customer environments is,
it turns out, exactly what network security engineering looks like at scale.

What I didn't have was the vocabulary, the framework, or the certifications to label what I was doing.
SCOR is giving me all three.

## The things I already knew

Reading through the SCOR material, I keep running into concepts I recognize from the field but am
now understanding more deeply. Control plane protection? I've been configuring CoPP on devices for
years without fully understanding the why behind it. Network segmentation via VLANs and access
control? Routine. Traffic telemetry with NetFlow? Part of my daily monitoring toolkit.

The SD-WAN chapter in the SCOR curriculum felt almost like a review session — except that it reframed
everything I'd been doing in terms of the security architecture it was protecting.

## The things that are genuinely new

Where I'm doing real learning: cryptography, PKI, and identity management. I understood that VPNs
encrypted traffic, but I hadn't dug into IKEv2 phase negotiation, certificate authority chains, or
exactly how 802.1X ties into RADIUS to authenticate a device before it ever touches the network.
Cisco Firepower/FTD is also new territory — I knew ASA firewalls existed at the edge of networks I
managed, but I wasn't the one configuring them.

That's the gap I'm closing, and it's a narrower gap than I expected.

## Why I'm making this move now

Network security isn't a separate discipline from infrastructure anymore. SD-WAN, SASE, and
cloud-delivered security have collapsed the distance between "networking people" and "security people."
The engineers who understand both layers — the physical and logical infrastructure AND the security
controls running on top of it — are increasingly the ones hiring managers can't easily find.

I'm studying for SCOR with an exam date of July 12, 2026. I'll be writing about what I learn here
as I go — from the perspective of someone who has spent a career building and maintaining the
infrastructure that security is designed to protect.

If you're a network engineer wondering whether security is a viable pivot, or a hiring manager looking
for someone who brings operational depth alongside security knowledge: that's exactly what I'm building
here.

---

*I'm currently studying for the Cisco CCNP Security SCOR 350-701 exam and documenting the transition
from WAN infrastructure management to network security engineering. Posts go up weekly.*
