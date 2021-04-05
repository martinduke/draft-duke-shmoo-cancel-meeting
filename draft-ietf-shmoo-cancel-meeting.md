---
title: Considerations for Cancellation of IETF Meetings
abbrev: Canceling Meetings
docname: draft-ietf-shmoo-cancel-meeting-03
date: {DATE}
category: bcp
ipr: trust200902
area: General
workgroup: shmoo

stand_alone: yes
pi: [toc, sortrefs, symrefs, docmapping]

author:
  -
    ins: M. Duke
    name: Martin Duke
    org: F5 Networks, Inc.
    email: martin.h.duke@gmail.com

normative:


informative:


--- abstract

The IETF firmly believes in the value of in-person meetings to discuss and
undestand issues. However, various emergencies can make a planned in-person
meeting impossible. This document provides criteria for making this judgment.

--- middle

# Introduction

One highlight of the IETF calendar is in-person general meetings, which happen
three times a year at various locations around the world.

Various major events may affect the suitability of a scheduled in-person IETF
meeting, though for some this may not be immediately obvious. For example:

* The meeting venue itself may unexpectedly close or otherwise be unable to meet
IETF meeting requirements due to a health issue, legal violation, or other
localized problem.

* A natural disaster could degrade the travel and event infrastructure in a
planned location and make it unethical to further burden that infrastructure
with a meeting.

* War, civil unrest, or public health crisis could make a meeting unsafe and/or
result in widespread national or corporate travel bans.

* An economic crisis could sharply reduce resources available for travel.

* Changes in visa policy or other unexpected governmental restrictions might
make the venue inaccessible to numerous attendees.

This document provides procedures for the IETF to decide to postpone, move, or
cancel an in-person IETF meeting.

# Conventions

The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be
interpreted as described in RFC 2119 {{?RFC2119}}.

In this document, the term "venue" refers to both the facility that houses the
sessions and the official meeting hotel(s).

# Decision Criteria and Roles

The LLC assesses whether or not an in-person meeting is logistically and
financially viable in light of events, and assembles information about various
travel restrictions that might impact attendance. The IESG and IRTF chair
assess if the projected attendance is sufficient for a viable in-person meeting.

## IETF LLC

The LLC is responsible for assessing the suitability of a venue for an IETF
meeting and is responsible for any reassessment in response to a major event
that leaves the prior conclusion in doubt. Where such an event occurs more that
twelve weeks before the start of the scheduled meeting, it is deemed a non-
emergency situation. Later events, up to and including the week of the meeting
itself, are deemed an emergency situation. 

In non-emergency situations, if the LLC determines the scheduled meeting clearly
cannot proceed (e.g. the venue has permanently closed), then it MUST consult
with the community on the reason(s) and its proposed remedy. In less clear
cases, the LLC SHOULD conduct a formal reassessment process that includes:

* Consulting with the community on the process timetable
* Consulting with the community on criteria to assess the impact of new
developments
* Consulting with the community on the form of the assessment report
* Publishing an assessment report and recommended remedy.
* Seeking approval of the IESG for the recommendation.

In emergency situations, which lack the time for a consultation process, this
document provides an IETF consensus on criteria the LLC MUST apply in its
assessment.

The LLC will collect information about the likely impact to in-person
attendance of national travel advisories, national and corporate travel bans,
quarantine requirements, etc. and report the results to the IESG.

The criteria in Section 3.1 of {{?RFC8718}} apply to venues that have changed
status. Specifically:

* Local safety guidelines allow the venue and hotels to host a meeting with the
expected number of participants and staff.

* It MUST be possible to provision Internet Access to the Facility and IETF
Hotels that allows those attending in person to utilize the Internet for all
their IETF, business, and day-to-day needs; in addition, there must be
sufficient bandwidth and access for remote attendees.  Provisions include, but
are not limited to, native and unmodified IPv4 and IPv6 connectivity, and global
reachability; there may be no additional limitation that would materially impact
their Internet use.  To ensure availability, it MUST be possible to provision
redundant paths to the Internet.

* A reasonable number of food and drink establishments are open and available
within walking distance to provide for the expected number of participants and
staff.

* Local health and public safety infrastructure should expect to have adequate
capacity to support an influx of visitors during the meeting week.

Finally, the LLC MUST assess the impact on its own operations, including:

* The number of critical support staff and contractors who can be at the venue

* The financial impact of continuing the meeting, or implementing any of the
possible remedies.

The LLC SHOULD cancel the meeting if it judges the meeting to be logistically
impossible or inconsistent with its fiduciary responsibilities.

In the event of considerations this document does not foresee, the LLC should
protect the health and safety of attendees and staff, as well as the fiscal
health of the organization, with approval from the IESG and a plan to seek a
later update of this document.

## IESG and IRTF Chair

If the LLC assesses there are no fundamental logistical or financial obstacles
to holding the meeting, the IESG and IRTF chair assess if projected attendance
is high enough to capture the benefit of an in-person meeting.

The IESG is discouraged from relying on a simple head count of expected event
attendance. Even dramatically smaller events with large remote participation may
be successful.  In addition to the LLC's estimate, the IESG might consider:

* Are many working groups and research groups largely unaffected by the
restrictions, so that they can operate effectively?

* Is there a critical mass of key personnel at most working group meetings to
leverage the advantages of in-person meetings, even if many participants are
remote?

# Remedies

In the event cannot be held at the scheduled time and place, the IETF has
several options. The remedies below should be consdered in light of these
principles, presented in no particular order:

* Hold the scheduled sessions of the meeting in some format

* Provide benefits of in-person interactions when possible

* Avoid exorbitant additional travel expenses due to last minute flight changes,
etc.

* The available time and resources allow the alternative to be adequately
prepared.

## Relocation

For attendees, the least disruptive response is to retain the meeting week but
move it to a more accessible venue. To the maximum extent possible, this will be
geographically close to the original venue. In particular, the IETF should
strive to meet the criteria in {{?RFC8718}} and {{?RFC8719}}.

Relocation that requires new air travel arrangements for attendees SHOULD NOT
occur less than one month prior to the start of the meeting.

## Virtualization

The second option, and one that has fewer issues with venue availability, is to
make the meeting fully remote. This requires different IETF processes and
logistical operations that are outside the scope of this document.

## Postponement

Although it is more disruptive to the schedules of participants, the next best
option is to delay the meeting until a specific date at which conditions are
expected to improve. The new end date of the meeting must be at least 30 days
before the beginning of the following IETF meeting.

Due to scheduling constraints at the venue, this will usually not be feasible.
However, it is more likely to allow attendees to recover at least some of their
travel expenses than other options.

## Cancellation

As a last resort, IETF may cancel the meeting totally. This is a last resort in
the event that worldwide conditions make it difficult for attendees to even
attend remotely. Not holding a meeting at all has wide implications for the
rhythm of IETF personnel policies, such as the nomination process and seating
of new officers.

Cancellation is likely the only practical alternative when emergencies occur
immeidiately before or during the meeting, so that there is no opportunity to
make other arrangements.

# Refunds

The IETF SHOULD NOT reimburse registered attendees for unrecoverable travel
expenses (airfare, hotel deposits, etc).

However, there are several cases where full or partial refund of registration
fees is appropriate:

* Cancellation SHOULD result in a full refund to all participants. It MAY be
prorated if some portion of the sessions completed without incident.
         
* Upon postponement, the LLC SHOULD offer refunds to registered attendees who
claim they cannot attend at the newly scheduled time.

* When the meeting becomes remote, the LLC SHOULD attempt to recover whatever
venue-related payments, past or future, it can and rebate this to registered
attendees, up to a maximum of their total cost of registration.

* The LLC SHOULD offer refunds to attendees whose nation of residence forbids,
or has issued a safety advisory against, visits to the host venue, even if the
in-person meeting will continue. It SHOULD NOT refund cancellations due to
employer policy or personal risk assessments.

These provisions intend to maintain trust between the IETF and its participants.
However, under extraordinary threats to the solvency of the organization, the
LLC may suspend them.

# Security Considerations

This document introduces no new concerns for the security of internet protocols.

# IANA Considerations

There are no IANA requirements.

--- back

# Acknowledgments

# Change Log

## Since draft-ietf-shmoo-cancel-meetings-02
* Added IRTF to IESG responsibilities

## Since draft-ietf-shmoo-cancel-meetings-01
* Added refund principles for hybrid meetings

## Since draft-ietf-shmoo-cancel-meetings-00
* Jay Daley's nits
* Distinguish the emergency and non-emergency process
* Eliminated USSTATE/UKFO references
* Clarified roles of LLC and IESG

## Since draft-duke-shmoo-cancel-meetings-01
* Change to WG draft

## Since draft-duke-shmoo-cancel-meetings-00
* Added mention of IRTF
* Discussed consensus on cancellation

## Since draft-duke-remote-meetings-00
* Defined "venue"
* Added principles for selecting remedies and rewrote alternatives.
* Added local authority travel advisories
* Added some criteria from IETF 109