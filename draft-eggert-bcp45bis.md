---

title: IETF Discussion List Charter
docname: draft-eggert-bcp45bis-latest
submissionType: IETF
date: {DATE}
category: bcp
submissionType: IETF
ipr: pre5378Trust200902
obsoletes: 3005
updates: 3683

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
  MOD-SOP:
    title: IETF Discussion List Moderator Team Standard Operating Procedures
    date: 2021-10-20
    author:
    - organization: IETF Discussion List Moderator Team
    target: "https://github.com/ietf/saa/blob/main/sop.md"

  MOD-UPC:
    title: Unprofessional Commentary
    date: 2021-10-20
    author:
    - organization: IETF Discussion List Moderator Team
    target:
      "https://github.com/ietf/saa/blob/main/unprofessional-commentary.md"

  LAST-CALLS:
    title: IETF Last Calls
    date: 2021-10-20
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/last-call"

  IETF-DISCUSS:
    title: IETF Discussion List
    date: 2021-10-20
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/ietf"

  IETF-ANNOUNCE:
    title: IETF Announcement List
    date: 2021-10-20
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/ietf-announce"

  ADMIN-DISCUSS:
    title: Discussion List for IETF LLC Administrative Issues
    date: 2021-10-20
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/admin-discuss"

  NOTE-WELL:
    title: Note Well
    date: 2021-10-20
    author:
    - organization: IETF
    target: "https://ietf.org/about/note-well/"

  NON-WG-LISTS:
    title: Non-Working Group Email List Guidelines
    date: 2021-10-20
    author:
    - organization: IETF
    target: "https://ietf.org/how/lists/nonwglist-guidelines/"

  ARCH-DISCUSS:
    title: Open Discussion Forum For Long/Wide-Range Architectural Issues
    date: 2021-10-20
    author:
    - organization: IAB
    target: "https://ietf.org/mailman/listinfo/architecture-discuss"

--- abstract

The Internet Engineering Task Force (IETF) discussion mailing list furthers the
development and specification of Internet technology through the general
discussion of technical, procedural, operational and other topics for which no
dedicated mailing lists exists. As this is the most general IETF mailing list,
considerable latitude in terms of topics is allowed, but there are posts and
topics that are unsuitable for this mailing list. This document defines the
charter for the IETF discussion list and explains its scope.

This document obsoletes RFC3005 and updates RFC3683.

--- middle

# Introduction {#intro}

The IETF discussion list {{IETF-DISCUSS}} furthers the development and
specification of Internet technology through the general discussion of
technical, procedural, operational and other topics for which no dedicated
mailing lists exists. As this is the most general IETF mailing list,
considerable latitude in terms of topics is allowed. However, there are posts
and topics that are unsuitable for this mailing list. This document defines the
charter for the IETF discussion list and explains its scope.

The IETF Note Well {{NOTE-WELL}} applies to discussions on the IETF discussion
list and all other IETF mailing lists, and requires conformance with the IETF
Guidelines for Conduct {{?RFC7154}} and the Anti-Harassment Policy {{?RFC7776}},
among others.

This document obsoletes {{?RFC3005}}, documenting the use of other mailing
lists for discussions that used to be in scope for the IETF discussion list,
referring to applicable policies such as the Guidelines for Conduct
{{?RFC7154}} and the Anti-Harassment Policy {{?RFC7776}}, and clarifying
moderation procedures. It also updates part of {{Section 1 of ?RFC3683}}, which
copies the list of "inappropriate postings" from {{?RFC3005}}. This list in
{{?RFC3683}} is hence updated by the new list in {{charter}} below.

# Charter for the IETF Discussion List {#charter}

The IETF discussion list is meant for discussions for which a more appropriate
list does not exist, such as discussions that do not fall within the scope of
any working group, area, or other established list. When discussions are
started on the IETF discussion list for which such a venue does exist, they
should be continued at that other venue as soon as this is pointed out.

When no dedicated mailing list exists for a topic, it may be preferable to
request the creation of one {{NON-WG-LISTS}} and announce the
availability of the new list on the IETF discussion list and on other
related lists, such as area lists, rather than discussing that topic on
the IETF discussion list.

Appropriate postings to the IETF discussion list include:

- Initial discussion of technical issues that are candidates for IETF work, but
  have not yet identified appropriate mailing lists.

- Questions and clarifications concerning practical aspects of IETF meetings,
  although most of these topics are better brought up on the discussion list for
  IETF LLC administrative issues {{ADMIN-DISCUSS}} or the attendee discussion
  list for a given IETF meeting.

- Announcements of conferences, events, or activities that are sponsored or
  endorsed by the IETF, IRTF, IAB or the Internet Society, although the IETF
  announcement list {{IETF-ANNOUNCE}} is the preferred list for these.

- Discussions of IETF direction, policy, and the standards process in general,
  when a more suitable list (such as the discussion list for IETF LLC
  administrative issues {{ADMIN-DISCUSS}}, the IAB discussion list for
  architectural issues {{ARCH-DISCUSS}}, a meeting attendees list, a
  process-oriented WG list, etc.) cannot be identified.

These topics used to be in scope for the IETF discussion list, but have since
moved to dedicated lists:

- Last Call discussions of documents now take place on the IETF
  Last Calls mailing list {{LAST-CALLS}}.

- Discussion of IETF administrative policies now takes place on the discussion
  list for IETF LLC administrative issues {{ADMIN-DISCUSS}}.

Inappropriate postings include:

- Advertising and other unsolicited bulk e-mail

- Discussion of subjects unrelated to IETF policy, meetings, activities, or
  technical topics

- Uncivil commentary, regardless of the general subject, per the IETF Note Well
  {{NOTE-WELL}}

- Announcements of conferences, events, or activities that are not sponsored or
  endorsed by the Internet Society or the IETF.

# Moderation {#mod}

The IETF Chair appoints *Moderators* (previously known as
the "sergeant-at-arms") for the IETF discussion list that are empowered to
restrict posting by a person, or to an email thread, when the content is
inappropriate and represents a pattern of abuse. They are encouraged to take
into account the overall nature of the postings by an individual and whether
particular postings are an aberration or typical.

Moderation of the IETF discussion list, including the handling of any appeals,
is to be guided by the IETF discussion list charter specified in
{{charter}}, and the related guidance from {{intro}} that applies to all mailing
lists. The moderators are intended to establish a self-moderation function on
the community, by the community. Because the IESG and IAB are in the appeals
chain for moderator decisions (see below), the IETF Chair therefore should not
appoint a moderator who is serving in such a role. If a moderator is selected
for the IESG or IAB, they will step down from the moderator team.

Apart from appointing moderators, the IETF Chair should refrain from the
day-to-day operation and management of the moderator team. The moderator team
will independently define, publish, and execute their roles according to a set
of operating procedures {{MOD-SOP}} and abuse patterns {{MOD-UPC}}.
The moderator team should reach out to the
IETF Chair for any conflict resolution in a timely manner.

Because a moderator serves at the discretion of the IETF Chair - even if the
IETF Chair is not otherwise involved in the operation of the moderator team -
any moderator decision can be appealed to the IETF Chair, per
{{!RFC2026}}. Decisions by the IETF Chair can be appealed to the IESG as whole,
again per {{!RFC2026}}.

# Security Considerations

The usual security considerations {{?RFC3552}} do not apply to this document.

Potential abuse of the moderation process for the suppression of undesired
opinions is counteracted by the availability of an appeals process, per
{{mod}}.

# IANA Considerations

This document does not request any IANA actions.

--- back

# Changes

{:aside}
> RFC Editor: Please remove this appendix before publication.

## Since draft-eggert-bcp45bis-08
- Update {{?RFC3683}}, because it copies text from {{?RFC3005}} that this
  document updates. See [this issue](https://github.com/larseggert/bcp45bis/issues/11).
- addressed [Éric Vyncke's IESG
  review](https://datatracker.ietf.org/doc/draft-eggert-bcp45bis/ballot/#draft-eggert-bcp45bis_eric-vyncke)
- addressed [Francesca Palombini's IESG
  review](https://datatracker.ietf.org/doc/draft-eggert-bcp45bis/ballot/#draft-eggert-bcp45bis_francesca-palombini)
  and [Carsten Bormann's
  ART ART review](https://mailarchive.ietf.org/arch/msg/art/ZnkYEl-9mRWfKXtzHVUu7u92QB0/)
- addressed [John Scudder's IESG
  review](https://datatracker.ietf.org/doc/draft-eggert-bcp45bis/ballot/#draft-eggert-bcp45bis_john-scudder)
- addressed [Roman Danyliw's IESG
  review](https://datatracker.ietf.org/doc/draft-eggert-bcp45bis/ballot/#draft-eggert-bcp45bis_roman-danyliw)
- addressed [Ben Kaduk's IESG
  review](https://datatracker.ietf.org/doc/draft-eggert-bcp45bis/ballot/#draft-eggert-bcp45bis_benjamin-kaduk)

## Since draft-eggert-bcp45bis-07
- incorporated suggestions from [Adrian
  Farrel](https://mailarchive.ietf.org/arch/msg/last-call/bt79VpEeM4iAiFVD5vtxHAa_kdc)
- incorporated some suggestions from [S
  Moonesamy](https://mailarchive.ietf.org/arch/msg/last-call/xQoWLovElvnS80ZPgHquAwJs3Mw)
- applied suggestions from [Robert
  Wilton](https://mailarchive.ietf.org/arch/msg/last-call/qCC0p5Yow7AOQLo8T3862jPl4i0)

## Since draft-eggert-bcp45bis-06

- applied a [suggestion from Lloyd
  Wood](https://mailarchive.ietf.org/arch/msg/ietf/jVF496BFjekl9eVx1q9sqDIqOCs)
  to add access dates to cited URLs
- fixes to this change log
- applied a suggestion from Brian Carpenter to change "unprofessional" to
  "uncivil"

## Since draft-eggert-bcp45bis-05

- clarification of list scope as [suggested by Brian
  Carpenter](https://github.com/larseggert/bcp45bis/pull/10)

## Since draft-eggert-bcp45bis-04

- use [RFC2026 appeals process](https://github.com/larseggert/bcp45bis/pull/7)
- addressed [comments from Barry
  Leiba](https://github.com/larseggert/bcp45bis/pull/6)
- quote cited text from Wikipedia

## Since draft-eggert-bcp45bis-03

- addressed [Robert Wilton's AD
  review](https://github.com/larseggert/bcp45bis/pull/5)

## Since draft-eggert-bcp45bis-02

- additional details about and guidelines for the SAA team, based on a
  [suggestion from Dhruv
  Dhody](https://github.com/larseggert/bcp45bis/pull/1)
- remove reference to the IETF 110 attendees list, since those lists are being
  removed by the secretariat shortly after each meeting

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

# Acknowledgements
{: numbered="no"}

The following people have made contributions to this document:

- Adrian Farrel
- Barry Leiba
- Ben Kaduk
- Brian Carpenter
- Carsten Bormann
- Christian Huitema
- Dhruv Dhody
- Eric Rescorla
- Éric Vyncke
- Francesca Palombini
- John Scudder
- Lloyd Wood
- Martin Thomson
- Robert Wilton
- S Moonesamy
- Stephen Farrell

Susan R. Harris authored {{?RFC3005}}, which this document replaces.
