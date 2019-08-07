# Licensing

Licensing defines the reuse and permissions around the project's code. A project
license defines how someone may use or redistribute a project's intellectual property
(IP). A contributor license agreement (CLA) defines the terms under which a
contributor grants a project the right to use and redistribute their IP.

1. [Why Document It?](#why-document-it)
2. [How To Document It?](#how-to-document-it)
    1. [Outbound License](#outbound-license)
    2. [Inbound License](#inbound-license)
3. [Example Licenses](#example-licenses)
    1. [Example Outbound Licenses](#example-outbound-licenses)
    2. [Example Inbound Licenses](#example-inbound-licenses)
4. [References](#references)

# Why Document It?

First, licensing your software appropriately can help protect you from various
kinds of warranty claims by users and limit your liability.

Second, a software license can limit _how_ someone uses your software. More permissive
licenses (like [MIT][mit] and [Apache 2][apache-2]) allowing modification and even
closed-source distribution and monetization. More restrictive "copyleft" licenses
(like [GPL-3][gpl-3]) require that copies and modified versions of the software
be kept open source and under the same license.

Finally, dictating the terms under which a contributor may grant rights in their
IP to a project can help disambiguate ownership and keep a project's code
flexible to change.

# How To Document It?

Two de-facto standards exist for documenting both outbound and inbound licenses.

## Outbound License

[GitHub expects a project's license to exist in a `LICENSE.txt` or
`LICENSE.md`][github-licensing] file in the root of your project's source code
repository.

[Choose a License][choose-license] is a great resource for helping guide you
through this decision. Adobe recommends using [Apache 2][apache-2] for most
projects, but [MIT][mit] is also acceptable for documentation and sample code.

## Inbound License

It is best to document whether you require an inbound license, also known as a
CLA, in your project's `CONTRIBUTING.md`. The Adobe open source [starter repo's
`CONTRIBUTING.md`][starter-repo-contributing] calls this out near the top of the
document.

Adobe projects going open source and into the public need to have external
contributors sign [Adobe's CLA][adobe-cla] before contributions from them can be
accepted.

Most small-scale open development projects don't need a CLA as services like
[GitHub by default treat the outbound license as the inbound
license][github-inbound-outbound].

# Example Licenses

## Example Outbound Licenses

On the "copyleft" spectrum, requiring that distributions of copies and modified
versions of the software remain open source:

- [GPL 3][gpl-3]

On the more permissive spectrum, allowing modification, commercialization and
redistribution:

- [BSD 3][bsd-3]
- [MIT][mit]
- [Apache 2][apache-2]

## Example Inbound Licenses

- [Adobe's Contributor Level Agreement][adobe-cla]
- [Microsoft's Contributor License Agreement][microsoft-cla]
- [Canonical's Contributor License Agreement][canonical-cla]

# References

1. [choosealicense.com][choose-license]
2. [Adobe's CLA][adobe-cla]
3. [Microsoft's CLA][microsoft-cla]
4. [Canonical's CLA][canonical-cla]
5. [GitHub Licensing Help Article][github-licensing]
6. [GitHub Inbound=Outbound Terms of Service][github-inbound-outbound]
7. [Adobe's Open Source Office's Starter Repo's `CONTRIBUTING.md`][starter-repo-contributing]
8. [MIT License][mit]
9. [Apache 2 License][apache-2]
10. [GPL 3 License][gpl-3]
11. [BSD 3 Clause License][bsd-3]
12. [Adobe's Open Source Guidelines For Use In Adobe Products][adobe-open-source-legalwiki]

[choose-license]: https://choosealicense.com
[adobe-cla]: https://opensource.adobe.com/cla.html
[microsoft-cla]: https://cla.microsoft.com
[canonical-cla]: https://www.ubuntu.com/legal/contributors
[github-licensing]: https://help.github.com/articles/licensing-a-repository/#determining-the-location-of-your-license
[github-inbound-outbound]: https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license
[starter-repo-contributing]: https://github.com/adobe/starter-repo/blob/master/CONTRIBUTING.md
[mit]: https://opensource.org/licenses/MIT
[apache-2]: https://www.apache.org/licenses/LICENSE-2.0
[gpl-3]: https://www.gnu.org/licenses/gpl-3.0.en.html
[bsd-3]: https://opensource.org/licenses/BSD-3-Clause
[adobe-open-source-legalwiki]: https://wiki.corp.adobe.com/display/legalwiki/Open+Source+Guidelines+for+use+in+Adobe+Products+and+Services
