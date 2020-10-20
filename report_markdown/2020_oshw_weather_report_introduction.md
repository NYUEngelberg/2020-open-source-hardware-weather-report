# Open Source Hardware Weather Report  2020


### Engelberg Center on Innovation Law & Policy

The Engelberg Center on Innovation Law & Policy at New York University School of Law provides a unique environment where scholars can examine the key drivers of innovation as well as the law and policy that best support innovation. By fostering interdisciplinary and collaborative research on innovation law and policy, the Engelberg Center attracts legal scholars and practitioners, technologists, economists, social scientists, physical scientists, historians, innovators, and industry experts who study the incentives that motivate innovators, how those incentives vary among creative endeavors, and the laws and policies that help or hinder them.


### Open Source Hardware Association

The Open Source Hardware Association (OSHWA) aims to foster technological knowledge and encourage research that is accessible, collaborative, and respects user freedom. OSHWA’s primary activities include hosting the annual Open Hardware Summit and maintaining the Open Source Hardware certification, which allows the community to quickly identify and represent hardware that complies with the community definition of open source hardware.


### Acknowledgements

This report is the result of discussions with a wide swath of the open source hardware community. We want to thank everyone who made themselves available to discuss their experiences in open source hardware and support this report, including the following people who agreed to be acknowledged below. While their input helped shape this report, their inclusion in this list is not necessarily intended to imply endorsement.

Kwabena Agyeman

Mitch Altman

Leon Anavi

Eric Carlson

Charles Duan

Lenore Edman

Salman Faris

Zach Fredin

Drew Fustini

Alicia Gibb

Josh Greenberg

Santana Jackson

Marcin Jakubowski

Toni Klopfenstein

Sophi Kravitz

Tod E. Kurt

Catarina Mota

Jie Qi

Elliott Rouse

Shah Selbe

Jan Suhr

Phillip Torrone

Jeffrey Yoo Warren

Juliana Zhang




# Introduction

Open source hardware has blossomed in the past 10 years.  In the decade since the first set of gatherings that would become the annual Open Hardware Summit, the open source hardware model has proven itself to be much more than an idea.  Open source hardware projects form the basis of robust community initiatives, expansive scientific research, and multi-million-dollar businesses.  The open source hardware community has developed a rich collection of organizations such as the Open Source Hardware Association (OSHWA), the Gathering for Open Science Hardware (GOSH), the Community BioSummit.  There is no question that open source hardware works as a business, as a community, and as an approach to creating.

One reason for open source hardware’s success is that it is a diffuse, dynamic approach to creation driven by a diverse community.  Although this diffuse nature is ultimately a strength, its diffuse nature can also make it hard to fully understand the state of the community at any moment in time.  This resource - which we are styling as a weather report - is designed to address that challenge by capturing the current moment in open source hardware.  Like a weather report, it describes current conditions and attempts to project into the future.

This weather report documents the state of open source hardware at the end of 2020.  Existing members of the community can use it to understand what is happening in other corners of the ecosystem, to help organize around universal challenges, and to collectively support opportunities. Newcomers to open source hardware can use the report to understand the current state of open source hardware, and to determine if an open source hardware approach fits well with their goals.

This resource is styled as a report, not a book.  It prioritizes identifying, organizing, and briefly introducing key concepts over exploring them in the fullest possible detail.  That approach is intended to make it easy to use this resource to survey the state of open source hardware.  Diving deeply into any element of open source hardware is beyond its scope.

The open source hardware community is far from monolithic.  In fact, not all communities that work within the open source hardware framework identify themselves as doing so.  Even self-acknowledged open source hardware communities can come from different traditions, sometimes only slightly aware of one another.

That can mean that some parts of the open source hardware community wrestle with problems solved long ago by others.  Similarly, all too often, disparate corners of the community are working on the same problems in parallel without the benefit of sharing resources.  Some people can  become frustrated when they try to join the community and are unable to find a guide that allows them to learn from what came before them.

This report is intended to begin a process of distilling information from disparate parts of the community into a common reference point.  While no report can be fully comprehensive, identifying common successes and challenges can make it easier for the community to coordinate within itself.

This report was originally designed to flow from an in-person workshop following the 2020 Open Hardware Summit.  When the summit became virtual as a result of the COVID pandemic, the workshop became a series of one-on-one interviews with many of the original invitees, as well as other members of the community.  The issues, questions, and challenges raised during these interviews formed the basis of this report.

This weather report captures a shared moment within the sprawling open source hardware community.   It identifies what works in open source hardware today, along with what does not work. Combined, these will help everyone understand when open source hardware can be effective - and when it is a poor match to an initiative’s goals.

It also identifies questions and roadblocks that are shared across the community.  Hopefully that will make everyone struggling with those challenges feel less alone.  It may also help the community coordinate to find solutions.  We hope that this report will help identify areas of opportunity for the community to build consensus, tools, and platforms that support open source hardware.  We also hope that it will help connect those disparate corners of the community to each other.

Open source hardware is a tool.  Like any tool, there are some problems that open source hardware strategies lend themselves to.  There are others where open source hardware simply does not make sense.  By capturing the state of open source hardware in 2020, we hope that existing community members can learn from their peers, new community members can find their way in, and former community members can find their way back.


## A Note on Terminology

The open source hardware community is broad. It includes multi-million-dollar companies, one-person hobby projects, and many initiatives in between.  While this diversity is a strength for the community, it can also create linguistic challenges.


### Open Hardware vs. Open Source Hardware

Although the use of ‘Open Hardware’ vs ‘Open Source Hardware’ once reflected two sides of a split within the community,[^1] at this point most people use the terms interchangeably.  This report follows that current convention and does not assign any relevance to the distinction.


### Open Hardware Projects

It can be complicated to identify the _thing_ at the heart of open source hardware.  _Hardware _can be too narrow because it fails to reflect the supporting documentation and code that make up a critical part of openness. Similarly, _product_ can suggest a focus on commercial open source hardware at the expense of other parts of the community.  While products make up an important, vibrant part of the open source hardware community, a commercial orientation is not required to be part of the open source hardware community.

This report uses _project_ to refer to the hardware, software, documentation, and community connected to a given piece of open source hardware.  The term encompasses commercial offerings as well as non-commercial offerings. Similarly, the _project team_ is the group of individuals who are primarily responsible for the project.  The team may be within a company, an entire company, an NGO, an academic research lab, or an informal collection of individuals.


### Open Hardware, Maker, and Low-Cost Hardware

This report focuses on open hardware.  While open hardware can overlap significantly with maker and low-cost hardware, the terms and concepts are not interchangeable.  These terms are also not universally defined.

_Open hardware_ is just that - hardware that is intentionally and purposefully open.  Open hardware can be created by an enthusiast at home or by a multi-million-dollar manufacturing infrastructure.  It is publicly documented and openly licensed, with source files and code available to all. Ideally, open hardware meets the [community definition of open source hardware](https://www.oshwa.org/definition/) maintained by the Open Source Hardware Association.

_Maker_ _hardware_ can be, but is not necessarily, open.  It tends to be created using distributed manufacturing tools, and is often designed to be user-buildable and user-serviceable.  Maker hardware tends to be oriented away from large industrial supply chains and toward individual or small group creators.

_Low-cost hardware_ is defined by its cost. It may be open or closed, DIY or industrial.  Its relatively low cost may make it more attractive to work with and deploy in challenging or resource-limited environments because it is inexpensive to replace.

Although each of these types of hardware share connections, it is helpful to recognize their distinctiveness.  Unlike “open hardware” and “open source hardware,” they cannot be used interchangeably.


# A Brief Background on Open Source Hardware

While this report celebrates the tenth anniversary of the Open Hardware Summit, the open source hardware community has roots that are much deeper.  The Open Source Hardware Association (OSHWA)’s [history](https://www.oshwa.org/research/brief-history-of-open-source-hardware-organizations-and-definitions/) of open source hardware begins with the work of [Bruce Perens](https://perens.com/) in 1997, and includes development of the [TAPR open source hardware license](https://tapr.org/the-tapr-open-hardware-license/) in 2007 and the OHANDA four freedoms mark in 2009.

2010 was the year of a gathering that would become the annual Open Hardware Summit and the creation of the community-derived [Open Hardware Definition](https://www.oshwa.org/definition/).  In 2012 OSHWA was formed as a home for the Open Hardware Definition and institutional organizer of the Open Hardware Summit.  OSHWA also developed a collection of best practices and guidance documents for creating open source hardware in response to community feedback and questions.  These documents became a common reference point for the community as it worked to develop open source hardware.

The Open Hardware Summit quickly grew into an annual focus for the open source hardware  community.  By 2016, OSHWA had also designated October as Open Hardware Month to make it easy to hold local celebrations of open source hardware beyond the annual summit.  These local celebrations included events around the world, featuring community members from an increasingly broad set of locations working within an increasingly broad set of contexts.

2016 also heralded the first Gathering on Open Science Hardware (GOSH) at CERN.  GOSH’s interests focus specifically on integrating open hardware into the sciences.  The first meeting produced the [GOSH manifesto](http://openhardware.science/gosh-manifesto/), codifying the goal of reducing barriers between diverse creators and users of scientific tools to support the pursuit and growth of knowledge.

As the community expanded, it became increasingly hard to easily identify hardware that complied with the open hardware definition.  In response, OSHWA created the open source hardware certification program in 2016.  [Version 2 of the program](https://certification.oshwa.org/), released in 2018, also provided an opportunity to [consolidate existing guidance documents and best practices](https://certification.oshwa.org/process/hardware.html). In a further attempt to help bring standardization to open hardware documentation, in 2019 the Open Know-How Working Group released Version 1.0 of the [Open Know-How Manifest Specification](https://app.standardsrepo.com/MakerNetAlliance/OpenKnowHow/src/branch/master/1).

During the same period, GOSH developed and released the [Global Open Science Hardware Roadmap](http://openhardware.science/global-open-science-hardware-roadmap/).  The result of years of community-focused development that included over 100 contributors, the 2018 roadmap charts a course to make open science hardware ubiquitous by 2025.  It emphasizes a ‘learn-support-grow’ model for creating a sustainable open science future.  Perhaps more importantly, the roadmap [continues to evolve and expand](https://gitlab.com/gosh-community/gosh-roadmap) through continuous community input.

Open source hardware licensing also evolved during this period.  Early licenses, such as the [TAPR Open Hardware License](https://tapr.org/the-tapr-open-hardware-license/) and [Solderpad Open Hardware License](https://solderpad.org/licenses/SHL-2.1/) attempted to adapt open source software licensing practices to hardware.  CERN also developed a set of licenses, releasing a popular [version 1.2](https://www.ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-1.2) in 2013.  In 2020, CERN released [version 2.0](https://www.ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2) of its license, now a suite of licenses designed to give users a choice between different approaches  to openness.

The institutions around open source hardware grew as well.  The _[Journal of Open Hardware](https://openhardware.metajnl.com/)_, the _[Journal of Open Engineering](https://www.tjoe.org/)_, and _[HardwareX](https://www.journals.elsevier.com/hardwarex/)_ emerged to document academic open hardware research.  The Deutsche Institut für Normung (DIN) - a German standardization organization - issued [DIN SPEC 3105](https://www.din.de/en/innovation-and-research/din-spec-en/business-plans/wdc-beuth:din21:305669958) for open source hardware.

Open hardware flourished during this decade of institutional growth. The [RepRap](https://reprap.org/wiki/RepRap) project created an entire desktop 3D printing industry.  A wide range of projects fused the worlds of art and technology.  In the wake of the earthquake and tsunami that devastated the Fukushima Daiichi Nuclear Power Plant, [Safecast](https://safecast.org/) created an open source geiger counter to track the radiation. More recently, ad hoc international teams have created scores of [open source medical devices](https://opensourcemedicalsupplies.org/library) to fight the COVID pandemic.  Throughout, open source hardware proved that it worked, driving adoption well beyond communities drawn to it because of an inherent belief in the power of openness.

The result of this history is a rich community of individuals, NGOs, and companies applying open source hardware principles to a wide range of challenges.  Oftentimes one of its greatest challenges is speaking to itself.  That is why this report consolidates information from a wide range of discussion into a single resource.

<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
     See the “Open Hardware vs. Open Source Hardware” section of OSHWA’s open source hardware history: https://www.oshwa.org/research/brief-history-of-open-source-hardware-organizations-and-definitions/
