---

title: IETF Discussion List Charter
docname: draft-eggert-bcp45bis-08
submissionType: IETF
date: {DATE}
category: bcp
submissionType: IETF
ipr: pre5378Trust200902
seriesno: 45
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
    title: Sergeant-at-Arms Standard Operating Procedures
    date: 2019-10-09
    author:
    - organization: IETF
    seriesinfo: commit c1abcb0
    target: "https://github.com/ietf/saa/blob/main/sop.md"

  MOD-UPC:
    title: Unprofessional commentary
    date: 2019-10-08
    author:
    - organization: IETF
    seriesinfo: commit e120305
    target:
      "https://github.com/ietf/saa/blob/main/unprofessional-commentary.md"

  LAST-CALLS:
    title: last-call -- IETF Last Calls
    date:
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/last-call"

  IETF-DISCUSS:
    title: ietf -- IETF-Discussion
    date:
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/ietf"

  IETF-ANNOUNCE:
    title: IETF-Announce -- IETF announcement list. No discussions.
    date:
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/ietf-announce"

  ADMIN-DISCUSS:
    title: admin-discuss -- Discussion list for IETF LLC administrative issues
    date:
    author:
    - organization: IETF
    target: "https://ietf.org/mailman/listinfo/admin-discuss"

  NOTE-WELL:
    title: Note Well
    date:
    author:
    - organization: IETF
    target: "https://ietf.org/about/note-well/"

  NON-WG-LISTS:
    title: Non-Working Group Email List Guidelines
    date:
    author:
    - organization: IETF
    target: "https://ietf.org/how/lists/nonwglist-guidelines/"

  ARCH-DISCUSS:
    title: Architecture-discuss -- open discussion forum for long/wide-range architectural issues
    date:
    author:
    - organization: IAB
    target: "https://ietf.org/mailman/listinfo/architecture-discuss"
    
--- abstract

The Internet Engineering Task Force (IETF) discussion mailing list furthers the
development and specification of Internet technology through the general
discussion of technical, procedural, operational, and other topics for which no
dedicated mailing lists exist. As this is the most general IETF mailing list,
considerable latitude in terms of topics is allowed, but there are posts and
topics that are unsuitable for this mailing list. This document defines the
charter for the IETF discussion list and explains its scope.

This document obsoletes RFC 3005 and updates RFC 3683.

--- middle

# Introduction {#intro}

The IETF discussion list {{IETF-DISCUSS}} furthers the development and
specification of Internet technology through the general discussion of
technical, procedural, operational, and other topics for which no dedicated
mailing lists exist. As this is the most general IETF mailing list,
considerable latitude in terms of topics is allowed. However, there are posts
and topics that are unsuitable for this mailing list. This document defines the
charter for the IETF discussion list and explains its scope.

The IETF Note Well {{NOTE-WELL}} applies to discussions on the IETF discussion
list and all other IETF mailing lists, and requires conformance with the IETF
Guidelines for Conduct {{?RFC7154}} and the Anti-Harassment Policy {{?RFC7776}},
among others.

This document obsoletes {{?RFC3005}}, as it documents the use of other mailing
lists for discussions that were previously in scope for the IETF discussion list,
refers to applicable policies such as the Guidelines for Conduct
{{?RFC7154}} and the Anti-Harassment Policy {{?RFC7776}}, and clarifies
moderation procedures. It also updates part of {{Section 1 of ?RFC3683}}, which
copies the list of "inappropriate postings" from {{?RFC3005}}. The list in
{{?RFC3683}} is hence updated by the new list in {{charter}}.

# Charter for the IETF Discussion List {#charter}

The IETF discussion list is meant for discussions for which a more appropriate
list does not exist, such as discussions that do not fall within the scope of
any working group, area, or other established list. When there is an existing venue 
for discussion, this should be noted and discussion should be moved there.

When no dedicated mailing list exists for a topic, it may be preferable to
request that one be created {{NON-WG-LISTS}} rather than discuss it on
the IETF discussion list.  Availability of the new list
may be announced on the IETF discussion list and on other
related lists, such as area lists.

Appropriate postings to the IETF discussion list include:

- Initial discussion of technical issues that are candidates for IETF work, but
  appropriate mailing lists have not yet been identified.

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
  endorsed by the IETF, IRTF, IAB or the Internet Society.

# Moderation {#mod}

The IETF Chair appoints *Moderators* (previously known as
the "sergeant-at-arms") for the IETF discussion list that are empowered to
restrict posting by a person, or to an email thread, when the content is
inappropriate and represents a pattern of abuse. They are encouraged to take
into account the overall nature of the postings by an individual and whether
particular postings are typical or an aberration.

Moderation of the IETF discussion list, including the handling of any appeals,
is guided by the IETF discussion list charter specified in
{{charter}}, and the related guidance from {{intro}} that applies to all mailing
lists. The moderators are intended to establish a self-moderation function on
the community, by the community. Because the IESG and IAB are in the appeals
chain for moderator decisions (see below), the IETF Chair therefore should not
appoint a moderator who is serving in such a role. If a moderator is selected
for the IESG or IAB, they will step down from the moderator team.

Apart from appointing moderators, the IETF Chair should refrain from the
day-to-day operation and management of the moderator team. The moderator team
will independently define, publish, and execute their role; see the current set
of operating procedures {{MOD-SOP}} and abuse patterns {{MOD-UPC}}.
The moderator team should reach out to the
IETF Chair for any conflict resolution in a timely manner.

Because a moderator serves at the discretion of the IETF Chair -- even if the
IETF Chair is not otherwise involved in the operation of the moderator team --
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



# Acknowledgements
{: numbered="no"}

Susan R. Harris authored {{?RFC3005}}, which this document replaces. In addition
to many technical contributions to the IETF, Susan authored a number of other
foundational documents, such as the original "IETF Guidelines for Conduct"
{{?RFC3184}} and the original "Tao of the IETF" {{?RFC3160}}.  Susan R. Harris
passed away in early 2022. This document is dedicated to her
memory, as a small token of appreciation of her many contributions.

The following people have made other contributions to this document:

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
- Subramanian Moonesamy
- Stephen Farrell
