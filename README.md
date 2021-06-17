# SLSA: Supply-chain Levels for Software Artifacts

Supply chain integrity attacks—unauthorized modifications to software
packages—have been
[on the rise](https://www.sonatype.com/hubfs/Corporate/Software%20Supply%20Chain/2020/SON_SSSC-Report-2020_final_aug11.pdf#page=7)
in the past two years, and are proving to be common and reliable attack vectors
that affect all consumers of software. The software development and deployment
supply chain is quite complicated, with numerous threats along the source ➞
build ➞ publish workflow. While point solutions do exist for some specific
vulnerabilities, there is no comprehensive end-to-end framework that both
defines how to mitigate threats across the software supply chain, and provides
reasonable security guarantees. There is an urgent need for a solution in the
face of the eye-opening, multi-billion dollar attacks in recent months (e.g.
[SolarWinds](https://www.solarwinds.com/sa-overview/securityadvisory),
[Codecov](https://about.codecov.io/security-update/)), some of which could have
been prevented or made more difficult had such a framework been adopted by
software developers and consumers.

Our proposed solution is
[Supply chain Levels for Software Artifacts](https://github.com/slsa-framework/slsa)
(SLSA, pronounced "salsa"), an end-to-end framework for ensuring the integrity
of software artifacts throughout the software supply chain. It is inspired by
Google's internal
"[Binary Authorization for Borg](https://cloud.google.com/security/binary-authorization-for-borg)"
which has been in use for the past 8+ years and is mandatory for all of Google's
production workloads. The goal of SLSA is to improve the state of the industry,
particularly open source, to defend against the most pressing integrity threats.
With SLSA, consumers can make informed choices about the security posture of the
software they consume.  

IMPORTANT: SLSA is an evolving specification and we are looking for wide-ranging
feedback via GitHub issues,
[email](https://groups.google.com/g/slsa-discussion), or [feedback
form](https://forms.gle/93QRfUqF7YY2mJDi9). SLSA is being developed as part of
the
[OpenSSF Digital Identity WG](https://github.com/ossf/wg-digital-identity-attestation)