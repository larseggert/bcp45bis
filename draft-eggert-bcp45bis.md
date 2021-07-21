---

title: IETF Discussion List Charter
docname: draft-eggert-bcp45bis-latest
date: {DATE}
category: bcp
ipr: pre5378Trust200902
obsoletes: 3005

stand_alone: yes
pi: [toc, sortrefs, symrefs, docmapping]

author:

-
  name: Lars Eggert
  org: NetApp
  street: Stenbergintie 12 B
  city: Kauniainen
  code: "02700"
  country: FI
  email: lars@eggert.org
  uri: "https://eggert.org/"

informative:
  SAA-SOP:
    title: Sergeant-at-Arms Standard Operating Procedures
    author:
    - organization: IETF Sergeants-at-Arms
    target: "https://github.com/ietf/saa/blob/master/sop.md"

  SAA-UPC:
    title: Unprofessional Commentary
    author:
    - organization: IETF Sergeants-at-Arms
    target:
      "https://github.com/ietf/saa/blob/master/unprofessional-commentary.md"

  LAST-CALLS:
    title: IETF Last Calls
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/last-call"

  IETF-DISCUSS:
    title: IETF Discussion List
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/ietf"

  IETF-ANNOUNCE:
    title: IETF Announcement List
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/ietf-announce"

  ADMIN-DISCUSS:
    title: Discussion List for IETF LLC Administrative Issues
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/admin-discuss"

  IETF-AHP:
    title: IETF Anti-Harassment Policy
    author:
    - organization: IETF
    target:
      "https://ietf.org/about/groups/iesg/statements/anti-harassment-policy/"

  NOTE-WELL:
    title: Note Well
    author:
    - organization: IETF
    target: "https://ietf.org/about/note-well/"

  NON-WG-LISTS:
    title: Non-Working Group Email List Guidelines
    author:
    - organization: IETF
    target: "https://ietf.org/how/lists/nonwglist-guidelines/"

--- abstract

The Internet Engineering Task Force (IETF) discussion mailing list furthers the
development and specification of Internet technology through the general
discussion of topics for which no dedicated mailing lists exists. As this is the
most general IETF mailing list, considerable latitude is allowed, but there are
posts that are unsuitable for this mailing list.

This document obsoletes RFC3005.

--- note_Note_to_Readers

Discussion of this draft takes place on the [GENDISPATCH working group mailing
list](mailto:gendispatch@ietf.org), which is archived at
[](https://mailarchive.ietf.org/arch/browse/gendispatch/).

Working Group information can be found at
[](https://datatracker.ietf.org/wg/gendispatch/); source code and the issues
list for this draft can be found at [](https://github.com/larseggert/bcp45bis).

--- middle

# Introduction

The IETF discussion list {{IETF-DISCUSS}} furthers the development and
specification of Internet technology through the general discussion of topics
for which no dedicated mailing lists exists. As this is the most general IETF
mailing list, considerable latitude is allowed. However, there are posts that
are unsuitable for this mailing list. This document defines the charter for the
IETF discussion list and explains its scope.

The IETF Note Well {{NOTE-WELL}} applies to discussions on the IETF discussion
list and all other IETF mailing lists, and requires conformance with the IETF
Guidelines for Conduct {{?RFC7154}} and the Anti-Harassment Policy {{IETF-AHP}},
among others.

# Charter for the IETF Discussion List {#charter}

The IETF discussion list is meant for discussions for which a more appropriate
list does not exist, such as discussions that do not fall within the area of
any working group, area or other established list. When discussions are started
on the IETF discussion list for which such venues do exist, they should be moved
there as soon as this is pointed out.

When no dedicated mailing list exists, it may be preferable to request the
creation of one {{NON-WG-LISTS}} and only announce the availability of the new
list on the IETF discussion list and on other related lists, such as area lists.

Appropriate postings to the IETF discussion list include:

- Initial discussion of technical issues that are candidates for IETF work, but
  have not yet identified appropriate mailing lists.

- Questions and clarifications concerning  practical aspects of IETF meetings,
  although most of these topics are better brought up on the discussion list for
  IETF LLC administrative issues {{ADMIN-DISCUSS}} or the attendee discussion
  list for a given IETF meeting.

- Announcements of conferences, events, or activities that are sponsored or
  endorsed by the Internet Society or the IETF, although the IETF announcement
  list {{IETF-ANNOUNCE}} is the preferred list for these.

These topics used to be in scope for the IETF discussion list, but have since
moved to dedicated lists:

- Last Call discussions of proposed protocol actions now take place on the IETF
  Last Calls mailing list {{LAST-CALLS}}.

- Discussion of IETF administrative policies now take place on the discussion
  list for IETF LLC administrative issues {{ADMIN-DISCUSS}}.

Inappropriate postings include:

- Advertising and other unsolicited bulk e-mail

- Discussion of subjects unrelated to IETF policy, meetings, activities, or
  technical topics

- Unprofessional commentary, regardless of the general subject

- Announcements of conferences, events, or activities that are not sponsored or
  endorsed by the Internet Society or the IETF.

# Security Considerations

The IETF Chair, the IETF Executive Director, or a sergeant-at-arms {{SAA-SOP}}
appointed by the Chair is empowered to restrict posting by a person, or of a
thread, when the content is inappropriate and represents a pattern of abuse
{{SAA-UPC}}. They are encouraged to take into account the overall nature of the
postings by an individual and whether particular postings are an aberration or
typical. Complaints regarding their decisions should be referred to the IAB.

# IANA Considerations

This document does not request any IANA actions.

--- back

# Acknowledgements

Susan R. Harris authored {{!RFC3005}}, which this document replaces.

# Changes

## Since draft-eggert-bcp45bis-02

- remove reference to the IETF 110 attendees list, since those lists are being
  removed by the secretariat shoryly after each meeting

## Since draft-eggert-bcp45bis-01

- applied a [suggestion from Brian
  Carpenter](https://mailarchive.ietf.org/arch/msg/gendispatch/-U2LWKf0VonKnQXs4jPEqIg_L_A)
- rephrased beginning of {{charter}}, as [suggested by Stephen
  Farrell](https://mailarchive.ietf.org/arch/msg/gendispatch/p73lu-D-WvQrbKBZ80c2T7bbBlQ/)
- incorporated a [suggestion from Christian
  Huitema](https://mailarchive.ietf.org/arch/msg/gendispatch/64LgqlIk0h62mAK09Muqn1ccqRE/)

## Since draft-eggert-bcp45bis-00

- added introduction, security considerations and IANA considerations sections
- added "note to readers" with pointers to the discussion list and the repo
- added references to IETF Sergeants-at-Arms procedures
- added references to various mailing lists for topics that used to be in scope
  for the IETF discussion list but no longer are
- added references to the Note Well and relevant other policies that apply

## Since RFC3005

- converted to Markdown and xml2rfc v3
- updated references (as part of the conversion)
- updated author information
- various formatting changes
