# Batch Connect - Reveal

A Batch Connect app designed for Open OnDemand that launches Reveal within a
batch job.

## Prerequisites

This Batch Connect app requires the following software be available on the
**compute nodes** that the batch job is intended to run on (**NOT** the
OnDemand node):

- [Reveal] v6.0-2024-07-10
- [Xfce Desktop] 4+

For VNC server support:

- [TurboVNC] 2.1+
- [websockify] 0.8.0+

For hardware rendering support:

- [X server]
- [VirtualGL] 2.3+

**Optional** software:

- [Lmod] 6.0.1+ or any other `module purge` and `module load <modules>` based
  CLI used to load appropriate environments within the batch job

[Reveal]: https://shearwatergeo.com/reveal-software/
[Xfce Desktop]: https://xfce.org/
[TurboVNC]: http://www.turbovnc.org/
[websockify]: https://github.com/novnc/websockify
[X server]: https://www.x.org/
[VirtualGL]: http://www.virtualgl.org/
[Lmod]: https://www.tacc.utexas.edu/research-development/tacc-projects/lmod

## Install

Clone the app from github then customise the 'form' and 'submit' settings as necessary.
