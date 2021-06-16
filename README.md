# SLSA: Supply-chain Levels for Software Artifacts

Supply-chain Levels for Software Artifacts (SLSA, pronounced _[salsa]_) is an
end-to-end framework for ensuring the integrity of software artifacts throughout
the software supply chain. The requirements are inspired by Google’s internal
"[Binary Authorization for Borg]" that has been in use for the past 8+ years and
that is mandatory for all of Google's production workloads.

**IMPORTANT:** SLSA is an evolving specification and we are looking for
wide-ranging feedback via GitHub issues, [mailing list], or [feedback form].
SLSA is being developed as part of the [OpenSSF Digital Identity WG].

## Overview

SLSA consists of:

1.  **[Standards](requirements.md):** Industry consensus on the definition of a
    "secure" software supply chain. There may be multiple standards to represent
    multiple aspects of security.
2.  **Accreditation:** Process for organizations to certify compliance with
    these standards.
3.  **[Technical controls](controls/README.md):** To record provenance and
    detect or prevent non-compliance.

Ultimately, the software consumer decides whom to trust and what standards to
enforce. In this light, accreditation is a means to transfer trust across
organizational boundaries. For example, a company may internally "accredit" its
in-house source and build systems while relying on OpenSSF to accredit
third-party ones. Other organizations may trust other accreditation bodies.

## Next

*   [What is SLSA?](about.md)
*   [SLSA Requirements](requirements.md)
*   [Detailed Example](walkthrough.md)

[Binary Authorization for Borg]: https://cloud.google.com/security/binary-authorization-for-borg
[OpenSSF Digital Identity WG]: https://github.com/ossf/wg-digital-identity-attestation
[feedback form]: https://forms.gle/93QRfUqF7YY2mJDi9
[mailing list]: https://groups.google.com/g/slsa-discussion
[salsa]: https://www.google.com/search?q=how+to+pronounce+salsa
