## SECTION 34 42 01

## GENERAL TECHNICAL REQUIREMENTS

## PART 1 GENERAL

## 1.01 SYSTEM DESCRIPTION

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
