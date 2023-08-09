# SECTION 34 42 01

## GENERAL TECHNICAL REQUIREMENTS for Specific Project MTD2207

### PART 1 GENERAL

### 1.01 SYSTEM DESCRIPTION

A. The Capital Metro Transportation Authority (CMTA) commuter rail system consists of a 32-mile
corridor from downtown Austin to Leander. In addition to CMTA passenger operations (host
railroad) two tenant railways also operate on the corridor Austin Western Railroad (AWRR)
providing freight transportation services and the Austin and Texas Central Railroad (AWCX) which
is a passenger excursion train.

B. Rail Traffic on CMTA’s Redline is controlled using Centralized Traffic Control (CTC) with a Positive
Train Control (PTC) overlay system, specifically Enhanced Automatic Train Control (E-ATC) as
defined in 49 CFR 236,1015 (e) (2). CMTA’s passenger trains and AWRR equipment are
“interoperable” and equipped with E-ATC. AWCX equipment is exempt per 49 CFR 236.1006(b)(4).
Tenant and host operations are temporally separated and do not operate on the same segment of
track at the same time. The complete system description can be found in The Contract Documents
section, CMTA PTC System Design Description (SDD), Revision A06.

C. CMTA’s (E-ATC) sub-system utilizes ElectrologIXS solid-state interlocking controllers and Audio
Frequency track circuits with (21) Cab speed codes / 40 Hz carrier manufactured by Alstom. E-
ATC is essentially a vital overlay on CMTA’s the wayside CTC system which consists of control
points and intermediate signal locations interconnected with Electrocode DC Coded track circuits
(EC5).

D. All freight engines and passenger vehicles (DMU’s) which operate on CMTA are equipped with
Alstom on-board Ultra Cab II (UCII) controllers, cab display units, receiver coils (at both ends of the
DMU or engine), propulsion and braking interfaces installed and programmed to respond to speed
codes received by the wayside E-ATC system to prevent train-to-train collisions, overspeed
derailments, incursions into work zones, and movement of trains through a mainline switch in the
proper position by performing speed enforcement based on aspects, vehicle speed and operator
actions.

E. CMTA’s RailComm LLC Train Control System (TCS) has been enhanced with (PTC (E-ATC)
functionality to permit the CMTA train dispatcher to issue and monitor route and signal requests,
Mandatory Directives (MD’s) or Temporary Speed Restrictions (TSR’s) on crossings or sections of
track as needed. RailComm manages and maintains CMTA’s custom RailComm DOC system
instance in a hosted, off premises, fully redundant environment. The CMTA interface to the
RailComm DOC system utilizes their DOC User Interface application. CMTA is responsible for the
local TCS workstations. Data communication between the TCS and wayside system utilizes a fiber
optic ring network communication system connecting each control point using Hirschmann RS-20
switches, GENISYS® protocols to exchange control and indication (CI) data.
F. CMTA road crossing warning systems utilize constant warning controllers of different manufactures
each utilizing a specific range of frequencies compatible with the E-ATC 40Hz Cab. Due to the 40
Hz carrier for E-ATC, tuned shunts are used for all crossing approach terminations, in addition
constant warning system frequencies of 86Hz and 114 Hz frequencies are not to be used due to
potential harmonic interference.

## 1.02 GENERAL REQUIREMENTS

### GENERAL TECHNICAL REQUIREMENTS
The Contractor shall comply with the following:
A. Design, furnish, install, test, and commission All PTC (E-ATC) and CTC system requirements and
associated Road Crossing warning system revisions and other works required to fully integrate the
“track upgrades” between West Kramer and West Serta. into CMTA’s existing CTC/EATC system
and as described herein. and will not be considered complete until final acceptance from CMTA
and compliant with the US Federal Railroad Administration (FRA).
1. The Contractor shall be responsible for the complete functional (verification) and operational
(validation) testing for all Work performed on this Project including all systems described in this
specification.

B. The Work to be performed under this Contract includes but is not limited to the final design,
application software, procurement, manufacture, documentation, delivery, installation, testing,
validation and commissioning of the CTC / EATC portion of the signal system required to be
modified due to the addition of the extended siding, including modified control points, intermediate
signal locations (if required), new and modifications to grade crossing warning controls, fiber
interfaces, associated subsystems, affected adjacent CTC/E-ATC locations, and the RailComm
DOC system configuration, new functionality, CMTA Workstation (GUI screens), modifications
required for the Control Office identified in the Contract Documents and in accordance with these
specifications. This includes the provision of preliminary engineering, braking calculations, track &
signal layout, profile, route & aspect; control line; location, detailed installation and commissioning
phasing plans and equipment, materials, cable, hardware, construction coordination and interfaces
required for final acceptance. The Contractor shall provide all management, planning, labor, data,
services, manuals, tools, system training and incidentals necessary to complete the Work in
accordance with the Contract requirements. The equipment furnished under this Contract shall be
supplied all new, with full warranty and in accordance with CMTA’s approved material list.

C. The Contract Documents section includes “reference only” drawings which include route & aspect
and partial control line drawings which provide an overview of the proposed CTC / E-ATC system
configuration required for the extended siding, signal aspects, call on functionality for return to train
and following moves, turnback functionality, parallel moves, independent switch control (ICS),
proposed EC track codes and the affected road crossing warning systems. These drawings also
show the track curve and profile information, MAS speeds, the proposed E-ATC system speed
codes applied based on the current permanent speed restrictions (PSR). E-ATC codes for
Mandatory Directives (MDs) and Temporary Speed Restrictions (TSR); time delay calculations etc.
are not indicated but must be considered. These drawings are intended as reference only to permit
the Contractor to prepare their submission. Final as installed drawings for the affected portion of
the existing system will be provided to the successful bidder upon award of the contract.
D. CMTA’s Vice President of Rail Operations or his duly authorized representative will be the final
authority for deciding whether a competitive item conforms to these requirements and complies
with the intention of this Specification.

E. This Specification is intended to be descriptive, but not restrictive, and is solely for showing the
type and quality of articles that will meet the approval of CMTA.
F. This Specification shall be considered as minimum requirements. Variations from the values listed
will be judged by CMTA as to their effect and ability to perform the intended work.
G. It shall be the responsibility of the Contractor to make certain that all systems, parts, and
components fit and function together properly.

GENERAL TECHNICAL REQUIREMENTS
H. Where brand, manufacturer or product names are shown in this Specification, they are included
only to establish identification and general descriptions of the item. Wherever such names appear,
the term "or approved equal" is considered to follow.

I. The limits of the Work shall be as shown on the Contract Drawings and as further specified herein.

J. Provisions of this Section apply to all Sections of the Signaling Specifications and any other
documents that are provided as part of the Contract Documents.

K. Provide new wayside equipment and material in accordance with the Contract Documents to
interface with existing systems. The Contractor is responsible for supplying any temporary
material/equipment to support phasing, installation, and testing.

L. Modify existing wayside equipment and material in accordance with the Contract Documents to
interface with the existing and new signal system equipment.

M. All decommissioned materials shall be delivered to CMTA at a site specified by CMTA's Vice
President of Rail Operations or his duly authorized representative.

N. Provide systems that are compliant with the applicable rules and regulations of 49CFR, parts 234,
235 and 236. Refer to the Contract Documents for the Contractor’s responsibility to determine if
any corrections or modifications are required to conform to these rules and regulations.

O. No circuit is considered to have met the requirement of the Specifications for function and safety
until it has been properly tested and validated in the field and in the control office.

P. Develop a multi-phase implementation plan subject to approval by CMTA, designed to minimize
the impact to train operations or cause excessive highway grade crossing warning, during all
phases of construction and testing. The Contractor’s implementation plan shall include strict,
supervised work procedures to mitigate an unsafe signaling condition from occurring or reduce the
effectiveness or quality of any grade crossing warning systems.

Q. Protect existing signal cabling and, where necessary, relocate existing cabling in order to prevent
damage during installation. Install new signal cabling as required to make the signal system
upgrades.

R. The Contractor’s circuit design, details and wiring diagrams shall be consistent in content and detail
in accordance with CMTA’s Drawing Standard 34 42.05.00 and CMTA typical wayside location
drawings.

S. Perform a thorough field survey of each location undergoing modification within the scope of the
McKalla project to verify the accuracy of the existing in-service circuit drawings, ELGX Executive,
vital and non-vital application software programs, track and profile and control line drawings, the
new and existing track configuration including track spacing, clearance points, location of existing
and new insulated joints, signal foundations, cable ducts, perform cable locates (FO,
Communications, Signal, locate underground utilities, verify crossing and signal sight lines, level
crossing angles, dimensions, locate crossing warning devices (proposed and existing) etc. prior to
implementing the design modifications.

T. Submit for CMTA approval, the final As-Built Book of Plans for each new or modified signal location.
Plans shall be signed and sealed by a Professional Engineer registered in the state of Texas.

U. Perform and document all inspections in accordance with CMTA’s General Instructions and PTC
Signal Systems Testing in accordance with Signal Specification Section 34 42 13.23, Signal
Systems Testing.

V. Perform factory and field (on-site) acceptance testing and commissioning of the signal system as
a normal part of the Work. The Contractor shall invite CMTA or their designated representative(s)
to observe the factory acceptance testing (FAT) as it is performed.

W. The Contractor shall configure and perform functional and operational simulation testing of the
various combined vital and non-vital software application programs for the new and modified
locations within the scope of the McKalla project using SATS (System Application Test System or
equivalent) to verify the combined software meets the overall system operational and functional
requirements. The Contractor shall present the final “McKalla” SATS (or equivalent) simulation
recording (demonstrating the operation of the system and logic with train movements), to CMTA
and its designated representatives as a step in the request for approval process.

X. Contractor-furnished software and hardware shall be new and manufacturer-certified.

Y. In the event of conflict as to placement of wayside signal structures, bungalows, cases, internal
equipment, cable etc., the correct placement will be determined by CMTA. The Contractor shall be
responsible for verifying site-specific conditions.

Z. Support and coordinate efforts with CMTA and other CMTA contractors, for the PTC modifications
to the RailComm Back Office/DOC System; and updating the PTCSP for resubmission to the FRA.

This includes but is not limited to:
1. Attendance and support at technical design review meetings with CMTA and its contractors to
address technical questions or issues, should they arise.
2. Working with CMTA to coordinate installation schedules with other contractors.
3. Enter into an agreement with RailComm to enable implementation of the CMTA
RailComm/DOC system modifications required for the McKalla project.
4. Formally define all TCS controls, indications, forms, MD, TSR’s, GUI display configuration and
special functionality modifications required to the RailComm for the project.
5. Develop and support the planning, execution of FAT, SAT and commissioning tests of the
RailComm/DOC system modifications.
6. Be on-site and conduct all testing and commissioning.
