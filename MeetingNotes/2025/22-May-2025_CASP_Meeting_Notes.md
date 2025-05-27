# 22 May 2025 Cybersecurity Automation Sub Project (CASP) Meeting Notes

- Meeting Date: 22 May 2025
- Time: 16:00 UTC (17:00 CET, 11:00 EST, 8:00 PST)

## I. Call to Order and Welcome

- Duncan (chair) called the meeting to order
- Permission was asked and granted, and meeting was recorded for notekeeping purposes

## II. Record Attendance
| Given Name | Family Name | Affiliation | Role |
|:-----------|:------------|:------------------------------------------------------------|:----------------------------|
| Duncan | Sparrell | sFractal | Secretary |
| Patrick | Maroney | AT&T | Member |
| John | Cavanaugh | IIS | Member |
| Jason | O'Connor | JHU APL | Member |
| Kevin | Cressman | HII | Member |

## III. Agenda
* Call to order
* Call for volunteers as Co-Chair
* Call for volunteers as Secretary
* OCA Interoperability Village SubProject Status
* Next Cybersecurity Automation Village / Interoperability Village
   * Hybrid or Virtual-only
   * Dates
   * Start list of Villages/Hamlets/Huts/....
* Cadence and date of next meeting(s)

## IV. Call for volunteers as Co-Chair
No volunteers

## V. Call for volunteers as Secretary
No volunteers

## VI. OCA Interoperability Village SubProject Status
Patrick reviewed status of the 
[OCA Interoperability Village](https://lists.oasis-open-projects.org/g/oca-interop-village)
(IoV) as it relates to CASP.
The intent had been to have IoV "CASP-ready" by this meeting 
but some architectural issues arose when reviewed by OASIS staff.
Even though Mesh Central implements a mesh architcture, 
it acheives it using a hub & spoke through a central point.
The 'router' was being implemented in AWS and OASIS was concerned with cost
based on AWS pricing 'by the bit'.
The alternative [Headscale](https://headscale.net/stable/) 
was evaluated by IoV and found to have an underlying mesh architecure,
such that two nodes could communicate directly without routing thru the central cloud server.
So IoV is choosing to switch to TailScale which is delaying being 'CASP-ready' by a month.

Patrick has the action item to have his 3 village neighborhoods converted to Headscale 
by our next meeting, and to document such that others can join (ie be "CASP-ready")
and we can begin listing huts/neighborhoods/village(s) etc to meet the CASP use case needs.

## VII. Next Cybersecurity Automation Village / Interoperability Village

### VII.A Hybrid or Virtual-only
The group discussed whether next Village 
should be virtual-only or hybrid - ie including an in-real-life (IRL) component.
AT&T offered to host the IRL segment but after considerable discussion,
the consensus of the group was that Village be virtual-only for the Oct/Nov Village
with the intent that the following village (eg March) be hybrid.

### VII.B Dates
Because of the decision to for the Village to be virtual-only, 
the exact date of the Village was not needed to be determined today, 
and hence was deferred.

### VII.C Architecture
During the IoV discussion, there was consensus that
the CASP portion of the next Village will focus on the use cases, the cybersecurity, 
and the automation. 
The CASP "huts" will ride on top of the Interoperability Village infrastructure 
for interconnections between huts/neighborhoods/villages. 
The 'value propositions' will be CASP responsiblity. 
The 'practioner use cases' will be CASP-focused but involve IoV interactions.
[Figure 1](./CaspIov.png) attempts to show this relationship.
Village participants are encouraged to sign up for 
Interoperatibility Village Sub 
Project (https://lists.oasis-open-projects.org/g/oca-interop-village) 
as they will need to understand, and want to influence the underlying infrastrucure.

There was consensus that the fall Village will focus on the 
exising use cases from past villages.
Participants can propose additional use cases 
but intent is to clean up exisitng use cases before focusing on 'the next use case'.

There was discussion of MQTT and interconnecting (and some revisit of the IoV/CASP interactions).
John created [Figure 2](./arch.png) during the meeting to capture the concepts.

### VII.D Start list of Villages/Hamlets/Huts/....
The group did not have time to go thru the details of 
what people intened to bring to the Village.
Participants are encouraged to start sharing via email what they intend to provide to the fall Village.

## VIII. Decisions Reached
* Next Village will be virtual-only
* Next Village will be in Oct or Nov, date TBD
* Next Village will start with exising use cases from past villages
   - Participants can propose additional use cases but intent is to clean up exisitng use cases before focusing on 'the next one'
* The CASP portion of the next Village will focus on the use cases, the cybersecurity, and the automation. It will ride on top of the Interoperability Village infrastructure for interconnections between huts/neighborhoods/villages. The 'value propositions' will be CASP responsiblity. The 'practioner use cases' will be CASP-focused but involve IoV interactions.
* CASP "huts" should use HeadScale (a change from MeshCentral) for IoV connectivity/infrastructure.

## IX. Action Items
* Any participants in previous plugfest (or anyone else) are encouraged to make pull requests to https://github.com/opencybersecurityalliance/casp/tree/main/Plugfests/2025-04-NorthernVirginia/Results so it looks like we actually had one. Please provide agenda, links to videos, copies of presentaions, etc.
* By CASP June meeting, Patrick to document Interoperability Village well enough for others to join in
* If interested in participating in next Village, please sign up for Interoperatibility Village Sup Project (https://lists.oasis-open-projects.org/g/oca-interop-village) as CASP rides on top of IoV for this fall.

## X. Cadence and date of next meeting(s)
It was agreed the cadence would continue momthly until we had more substance.
The next meeting will be 12-June at 16:00 UTC (17:00 CET, 11:00 EST, 8:00 PST).
The July meeting will be 24-July at 16:00 UTC (17:00 CET, 11:00 EST, 8:00 PST).
As we get nearer to the Villaged, it is likely we will meet more frequently.

Members are encouraged to continue to contribute via email and github between meetings.
