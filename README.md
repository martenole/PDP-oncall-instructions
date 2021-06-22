# PDP Oncall Documentation
The PDP oncall is the main contact for Run Coordination (RC) with regard to physics data processing. This includes the O2 framework, reconstruction, calibration and GPU processing as well as the connection to EOS and the CCDB.

The responsible people for the PDP operation are:
| Function                      | Name           | Phone  | Email          |
|-------------------------------|----------------|--------|----------------|
| System Run Coordinator        | David Rohr     | 16-8257 | <drohr@cern.ch>          |
| deputy System Run Coordinator | Ole Schmidt    | 66328  | <ole.schmidt@cern.ch>    |
| Technical Coordinator         | Ruben Shahoyan | 16-5391 | <ruben.shahoyan@cern.ch> |
| Project Leader                | Andreas Morsch | 16-0347 | <andreas.morsch@cern.ch> |

Hints:
- CERN mobile numbers (16-\*) can be reached via +41-75-411-(Last 4 digits)
- CERN numbers can be reached via +41-2276-(5 digits)

## Booking oncall shifts
Oncall shifts are always booked for a period of 7 consecutive days and thus include one weekend. In order to avoid having to handover and coordinate with the next oncall on a Sunday, shifts are always booked from Tuesday (starting at 12.01am) until Monday (ending at 11.59pm). Shifts can be booked via SAMS: <https://alice-glance.cern.ch/alice/sams/shift/booking?start_date=2021-07-01&end_date=2021-07-31&subsystem%5B%5D=41&view=shift>. In order to book a shift you need to have the permission in SAMS. Permission can be given to you by the SRCs, please contact David or Ole.

> *If you coordinate with a collegue and split the oncall shift block of 7 days among each other it is also fine, as long as always the full 7 days are booked.*

As oncall you will need to be reachable via a CERN phone number. This can be a CERN mobile number if you have one or you can use the CERNphone app which is described here: <https://cernphone.docs.cern.ch/>. Please make sure that your phone number in SAMS (<https://alice-glance.cern.ch/alice/sams/member/profile?view=permissions>) is correct and that you can receive calls via this number prior to the start of your shift. Technically the requirement for an oncall is that he/she should be able to physically come to P2 within 15 minutes during his/her shift. For PDP it is sufficient if one member of the group is in the local area and can come onsite if necessary. If you as oncall are not in the local area please make sure that someone else is available. So you can also do your shifts completely remotely.

## Checklist before starting your shift
- [x] subscribe to the egroup alice-p2info and alice-pdp-oncalls (search for the name at https://e-groups.cern.ch/)
- [x] check that your phone number in SAMS is correct (https://alice-glance.cern.ch/alice/sams/member/profile)


## Meeting duties
**Monday at 4pm:** Software & Computing Meeting (PDP group meeting)\
Learn about updates from PDP side which should be communicated to RC during the daily meeting on the following day.

**Tuesday at 10.30am** Weekly RC Meeting\
Follow information from RC and other central systems, etc. The weekly meeting is intended for general announcements and presentations. Typically there will not be a report by the PDP oncall at this meeting.

**RC daily meeting at 4.30pm** (except for Mondays, since this overlaps with the PDP group meeting)\
Report updates from PDP side and stay informed about what is happening at P2. Our decision is to report a larger update from PDP only once a week and to do so on Tuesdays, because there might be news from the PDP meeting the day before to report. Before the daily meeting on Tuesday you should receive a mail by the SRCs, Ruben and Chiara with updates from PDP which should be reported at the meeting. In case this is a long list please send a mail to RC prior to the beginning of the meeting so that the information can be put in the minutes beforehand. Should you not receive a mail an hour before the RC meeting starts please ask the SRCs, Ruben and Chiara for an update. In case no one from the Event Display (ED) is connected we can report the ED status from the PDP meeting on Monday to RC.\
At the other daily RC meetings we will report from the PDP side only in case there is something urgent to discuss or upon request by RC with respect to a specific topic. In that case please check with the person responsible (e.g. the assignee of the jira ticket). Still it is of course important to follow the meetings to be up to date with respect to current activities at P2.

## Monitoring tools
The EPN InfoLogger can be accessed at:\
<http://alihlt-gw-prod.cern.ch:8081/>

*Further monitoring webpages are under development and will be linked here in the future.*

> Some monitoring tools are only available from the CERN GPN, so you might need to configure a SOCKS proxy if you are accessing it from home. You can find documentation on how to set this up at <https://security.web.cern.ch/recommendations/en/ssh_browsing.shtml>. For example if you are using linux you can run a proxy by running inside the terminal\
`ssh -D 8080 lxtunnel.cern.ch -N -l <youruser>`\
Afterwards you can add an extension to your browser (for example FoxyProxy Standard for Firefox) and add a socks5 proxy with the hostname `localhost` and port number `8080`.


## Expert list
| **What**                    | **Who**           |
|-----------------------------|-------------------|
| Synchronous processing, GPU | [David](https://phonebook.cern.ch/phonebook/#search/?query=David+Rohr)             |
| EOS, CCDB                   | [Latchezar](https://phonebook.cern.ch/phonebook/#search/?query=Latchezar+Betev), [Costin](https://phonebook.cern.ch/#search/?query=Costin+Grigoras) |
| Calibration                 | [Chiara](https://phonebook.cern.ch/phonebook/#search/?query=Chiara+Zampolli)            |
| Reconstruction              | [Ruben](https://phonebook.cern.ch/phonebook/#search/?query=Ruben+Shahoyan)             |
| Framework                   | [Giulio](https://phonebook.cern.ch/phonebook/#search/?query=Giulio+Eulisse)            |
| Event Display               | [Julian](https://phonebook.cern.ch/phonebook/#search/?query=Julian+Myrcha)  |
| FairMQ (external)           | [Alexey](https://phonebook.cern.ch/phonebook/#search/?query=Alexey+Rybalchenko)  |
| DataDistribution (external) | [Gvozden](https://phonebook.cern.ch/phonebook/#search/?query=Gvozden+Neskovic)  |
| InfoLogger (external)       | [EPN oncall](https://alice-glance.cern.ch/alice/sams/public/arc_display) |

