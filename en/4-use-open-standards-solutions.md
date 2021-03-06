---
layout: default
title:  "4. Use open standards and solutions"
lang: en
altLang: fr
altLangPage: 4-utiliser-normes-solutions-ouvertes
---
<div class="dpgn-section-intro-standard">

**[TODO: Add/revise introductory text]**
{: .dpgn-data-ignore}

</div>

<div class="dpgn-section-guidelines">

**Guidelines:**

<!-- markdownlint-disable MD032 -->
- TOC
{:toc}
<!-- markdownlint-enable MD032 -->

</div>

<div class="dpgn-section-guidelines-related">

**Related guidelines:**

{% include functions/guideline-links.html guidelines="1.2, 3.2, 8.1, 8.2, 9.2, 10.2" samePage=false includeStandardTitle=true %}

</div>

<section class="dpgn-section-guideline">

## 4.1 Leverage open standards and embrace leading practices, including the use of open source software where appropriate

<div class="dpgn-section-intro-guideline">

Build technology that uses open standards to ensure your system works and communicates with other products or systems, and can easily be upgraded and expanded.

Adopting and using open standards means you can:

- move between different technologies when you need to, avoiding vendor lock-in
- quickly and easily change your service when you need to
- increase compatibility with all stakeholders
- open up the range of companies you can purchase from as more of them are likely to use the same standard as you
- access a wider range of both open source and proprietary software vendors

Our choices for hosting infrastructure, databases, software frameworks, programming languages and the rest of the technology stack should seek to avoid vendor lock-in and match what successful modern consumer and enterprise software companies would choose today. In particular, digital services teams should consider using open source software, cloud-based, and commodity solutions across the technology stack, because of their widespread adoption and support by successful consumer and enterprise technology companies in the private sector.

Open source software (OSS) tends to use and help define open standards and publicly available specifications. OSS products are, by their nature, publicly available specifications, and the availability of their source code promotes open, democratic debate around their specifications, making them both more robust and interoperable.

Using open source software means you can benefit from:

- solving common problems with readily available open source technology
- more time and resource for customised solutions to solve the rare or unique problems
- lower implementation and running costs

</div>

<section class="dpgn-section-checklist">

### Checklist

**[TODO: Add/revise checklist items]**

- Use open standards and open source software at every layer of the technology stack
- Factor in the use of open Standards and open source software when calculating total cost of ownership of a solutions including exit or transition costs
- Avoiding lock-in to any proprietary solutions where open source software and/or open standards are available
- Ensure that software can be deployed on a variety of commodity hardware types

**Government of Canada Cloud Adoption Strategy:**
{: .dpgn-data-ignore}

- Cloud services are identified and evaluated as the principal delivery option when initiating IT investments, initiatives, strategies and projects.
- In considering how to manage security risks, departments and agencies must follow the [GC Cloud Security Risk Management Approach and Procedures](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/cloud-services/cloud-security-risk-management-approach-procedures.html) and the [Direction on the Secure Use of Commercial Cloud Services: Security Policy Implementation Notice (SPIN)](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/cloud-services/direction-secure-use-commercial-cloud-services-spin.html).
- Departments and agencies may deploy solutions that have data-categorization requirements that fall outside of a particular cloud security control profile, as described in the [Government of Canada Security Control Profile for Cloud-Based GC IT Services](https://www.canada.ca/en/government/system/digital-government/modern-emerging-technologies/cloud-computing/government-canada-security-control-profile-cloud-based-it-services.html), with appropriate risk-mitigation measures that have been developed in consultation with GC security partners.
- To ensure, to the greatest extent possible, the GC???s continuous access to sensitive data, departments and agencies must comply with the [Direction for Electronic Data Residency](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/cloud-services/direction-electronic-data-residency.html).
- To ensure business continuity and to manage risks, departments and agencies will develop an appropriate exit strategy before using cloud services.
- Departments and agencies should consider portability and interoperability of services when designing cloud-based solutions.

</section>

<section class="dpgn-section-guides">

### Implementation guides

- [Socle Logiciels Libres (France)](https://references.modernisation.gouv.fr/socle-logiciels-libres)
- [Logiciels libres et ouverts - Guide d'analyse de maturit?? (Qu??bec)](https://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/logiciels_libres/pollo.pdf)
- [Logiciels libres et ouverts - Guide d'analyse du co??t total de propri??t?? (Qu??bec)](https://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/logiciels_libres/ctp.pdf)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-open-standards-solutions} [Working with open standards (Service Manual (UK))](https://www.gov.uk/service-manual/technology/working-with-open-standards)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-open-standards-solutions} [Choosing technology: an introduction (Service Manual (UK))](https://www.gov.uk/service-manual/technology/choosing-technology-an-introduction)
- [Australian Government ICT Policy Guides and Procurement (AU)](http://finance.gov.au/policy-guides-procurement/)
- [Australian Government Open Source Software Policy (AU)](http://www.finance.gov.au/sites/default/files/australian-government-open-source-software-policy-2013.pdf)
- [DoD Open Source Software FAQ (US)](http://dodcio.defense.gov/Open-Source-Software-FAQ/)
- [DoD Memorandum on Guidance Regarding Open Source Software (US)](http://dodcio.defense.gov/Portals/0/Documents/OSSFAQ/2009OSS.pdf)
- [W3C Standards (W3C)](https://www.w3.org/standards/)
  - [Web Design and Applications - W3C Web design standards (W3C)](https://www.w3.org/standards/webdesign/)
  - [Web of Devices (W3C)](https://www.w3.org/standards/webofdevices/)
- [OASIS Standards (oasis-open.org)](https://www.oasis-open.org/standards)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-cloud-first} [Government of Canada Right Cloud Selection Guidance](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/cloud-services/government-canada-right-cloud-selection-guidance.html)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-cloud-first} [Government of Canada Security Control Profile for Cloud-Based GC IT Services](https://www.canada.ca/en/government/system/digital-government/modern-emerging-technologies/cloud-computing/government-canada-security-control-profile-cloud-based-it-services.html)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-cloud-first} [Government of Canada Cloud Adoption Strategy](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/cloud-services/government-canada-cloud-adoption-strategy.html)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-cloud-first} [Government of Canada White Paper: Data Sovereignty and Public Cloud](https://www.canada.ca/en/government/system/digital-government/modern-emerging-technologies/cloud-computing/gc-white-paper-data-sovereignty-public-cloud.html)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-cloud-first} [Government of Canada Cloud Security Risk Management Approach and Procedures](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/cloud-services/cloud-security-risk-management-approach-procedures.html)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-cloud-first} [Direction on the Secure Use of Commercial Cloud Services: Security Policy Implementation Notice (SPIN)](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/cloud-services/direction-secure-use-commercial-cloud-services-spin.html)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-cloud-first} [Direction for Electronic Data Residency](https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/cloud-services/direction-electronic-data-residency.html)

</section>

<section class="dpgn-section-solutions">

### Reusable solutions

- [Web Experience Toolkit (WET)](http://wet-boew.github.io/wet-boew/index-en.html)

</section>

<section class="dpgn-section-similar">

### Similar resources

- [Open Standards (Open First Whitepaper (GC))](https://github.com/canada-ca/Open_First_Whitepaper/blob/master/en/2_Open_Standards.md)
- [Open Source Software Use (Open First Whitepaper (GC))](https://github.com/canada-ca/Open_First_Whitepaper/blob/master/en/3_Open_Source_Software_Use.md)
- [Natural Resources Canada Free and Open Source Software Licensing Primer (GC)](https://ftp.maps.canada.ca/pub/nrcan_rncan/publications/STPublications_PublicationsST/295/295663/cgdi_ip_33_e.pdf)
- [Logiciels libres et ouverts - Guide de r??f??rence (Qu??bec)](https://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/logiciels_libres/ll.pdf)
- [Politique du libre (Montr??al)](https://github.com/VilledeMontreal/politique-libre/blob/master/Politique/PolitiqueDuLibre.md)
- [18F Open Source Policy (US)](https://github.com/18F/open-source-policy/blob/master/policy.md)
- [3. Be open and use open source (Technology Code of Practice (UK))](https://www.gov.uk/guidance/be-open-and-use-open-source)
- [4. Make use of open standards (Technology Code of Practice (UK))](https://www.gov.uk/guidance/make-use-of-open-standards)
- [9. Use open standards and common platforms (Digital Service Standard (Ontario))](https://www.ontario.ca/page/digital-service-standard#section-9)
- [Three-Step Software Solutions Analysis (Federal Source Code Policy (US))](https://sourcecode.cio.gov/Three-Step-Software-Solutions-Analysis/)
- [1. Comply with Government of Canada acts, policies, standards and directives (Plan - Digital Design Playbook (ISED)) (internal to GC only)](http://www.gcpedia.gc.ca/wiki/DDPlayBook_Plan#1._Comply_with_Government_of_Canada_acts.2C_policies.2C_standards_and_directives)
- [2. Reuse, improve and share technological solutions where appropriate (Do - Digital Design Playbook (ISED)) (internal to GC only)](http://www.gcpedia.gc.ca/wiki/DDPlayBook_Do#2._Reuse.2C_improve_and_share_technological_solutions_where_appropriate)
- [9. Deploy in a flexible hosting environment (Digital Services Playbook (US))](https://playbook.cio.gov/#play9)

</section>
</section>

<section class="dpgn-section-guideline">

## 4.2 Design for services and platforms that are seamless for Canadians to use no matter what device or channel they are using

<div class="dpgn-section-intro-guideline">

In order to limit costs, avoid duplication of effort and provide a consistent client experience when using various services, the reuse and adaptation of existing technological solutions is encouraged. If the development of new solutions is required, consider the ability of others to reuse and adapt your work as this will provide additional value on an organizational level.

Using common, proven government solutions, approaches, and platforms will help the government:

- meet the needs of your users by building with proven solutions
- make users' experience of government more consistent, which generates trust
- save time and money by reusing things that are already available

Interoperability is a characteristic of a product or system, whose interfaces are completely understood, to work with other products or systems, present or future, in either implementation or access, without any restrictions. Interoperability should be ensured, via the use of open standards.

Application Program Interfaces (APIs) are a means by which business functionality is exposed digitally. They are building blocks that are critical to the successful delivery of government online digital services and expanding service delivery to third party providers. They can also enable greater interoperability between services, optimized experiences across devices and can even lead to innovative new services by enabling third party products to work seamlessly with Government of Canada systems.

</div>

<section class="dpgn-section-checklist">

### Checklist

- Ensure content and functionality is optimized for a wide range of devices, including mobile devices and voice assistants, enabling users to be successful with their device of choice
- Build services that are API-centric services, which execute most, if not all, functionality through API calls (e.g., connecting frontend to backend through an API)
- Plan out API access from the beginning, designing services to be able to safely and securely expose functionality to other systems and the public.
- Design APIs to be compete but also minimal, ensuring the expected functionality is provided but with as few public members per class and as few classes as possible. This makes it easier to understand, remember, debug and change the API.
- Design APIs to have clear and simple semantics to make common tasks easy. Rare tasks should still be possible but not the focus. Avoid being overly general, optimizing specific use cases.
- Design APIs to be intuitive so that a semi-experienced user can be successful with minimal assistance from the documentation and programmers can easily understand code that uses the API.
- Design APIs to be easy to memorize by implementing a consistent and precise naming convention. Use plain language and recognizable patterns and concepts, avoiding abbreviations where possible.

</section>

<section class="dpgn-section-guides">

### Implementation guides

- [Canada.ca Content and Information Architecture Specification](https://www.canada.ca/en/treasury-board-secretariat/services/government-communications/canada-content-information-architecture-specification.html)
- [Canada.ca Content Style Guide](https://www.canada.ca/en/treasury-board-secretariat/services/government-communications/canada-content-style-guide.html)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-performance-availability-scalability} [Designing for different browsers and devices (Digital Service Standard (UK))](https://www.gov.uk/service-manual/technology/designing-for-different-browsers-and-devices)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-open-standards-solutions .dpgn-digital-architectural-enable-interoperability} [API technical and data standards (Government Digital Service (UK))](https://www.gov.uk/guidance/gds-api-technical-and-data-standards)
- {: .dpgn-digital-architectural .dpgn-digital-architectural-enable-interoperability} [Developing cross-government API data and technical standards (Government Digital Service blog (UK))](https://gdstechnology.blog.gov.uk/2018/02/13/developing-cross-government-api-data-and-technical-standards/)
- [How to measure digital take-up (Service Manual (UK))](https://www.gov.uk/service-manual/measuring-success/measuring-digital-take-up)
- [Encouraging people to use your digital service (Service Manual (UK))](https://www.gov.uk/service-manual/helping-people-to-use-your-service/encouraging-people-to-use-your-digital-service)

</section>

<section class="dpgn-section-solutions">

### Reusable solutions

- {: .dpgn-digital-architectural .dpgn-digital-architectural-maximize-reuse} [Web Experience Toolkit (WET)](http://wet-boew.github.io/wet-boew/index-en.html)

</section>

<section class="dpgn-section-similar">

### Similar resources

- [3. Be consistent (Digital Service Standard (Ontario))](https://www.ontario.ca/page/digital-service-standard#section-3)
- [6. Consistent and responsive design (Digital Service Standard (AU))](https://guides.service.gov.au/digital-service-standard/6-consistent-and-responsive/)
- [4. Design the service from start to finish (Digital Service Standard (Ontario))](https://www.ontario.ca/page/digital-service-standard#section-4)
- [2. Address the whole experience, from start to finish (Digital Services Playbook (US))](https://playbook.cio.gov/#play2)
- [14. Encourage everyone to use the digital service (Digital Service Standard (UK))](https://www.gov.uk/service-manual/service-standard/encourage-everyone-to-use-the-digital-service)
- [11. Encourage people to use digital services (Digital Service Standard (Ontario))](https://www.ontario.ca/page/digital-service-standard#section-11)

</section>
</section>
