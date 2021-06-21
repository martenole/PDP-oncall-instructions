# PDP Oncall Documentation
The PDP Oncall is the main contact for Run Coordination (RC) with regard to the physics data processing. This includes the O2 framework, reconstruction, calibration and GPU processing as well as the connection to EOS and the CCDB.

The responsibles for the PDP operation are:
| Function                      | Name           | Phone  | Email          |
|-------------------------------|----------------|--------|----------------|
| System Run Coordinator        | David Rohr     | 16-8257 | drohr          |
| deputy System Run Coordinator | Ole Schmidt    | 66328  | ole.schmidt    |
| Technical Coordinator         | Ruben Shahoyan | 16-5391 | ruben.shahoyan |
| Project Leader                | Andreas Morsch | 16-0347 | andreas.morsch |

Hints:
- CERN mobile numbers (16-\*) can be reached via +41-75-411-(Last 4 digits)
- CERN numbers can be reached via +41-2276-(5 digits)

## Booking Oncall shifts
Oncall shifts are always booked for a period of 7 consecutive days and thus include one weekend. In order to avoid having to handover and coordinate with the next oncall on a Sunday, shifts are always booked from Tuesday (starting at 12.01am) until Monday (ending at 11.59pm). Shifts can be booked at SAMS: <https://alice-glance.cern.ch/alice/sams/shift/booking?start_date=2021-07-01&end_date=2021-07-31&subsystem%5B%5D=41&view=shift>. In order to book a shift you need to have the permission in SAMS. Permission can be given to you by the SRCs, pleace contact David or Ole.

As oncall you will need to be reachable via a CERN phone number. This can be a CERN mobile number if you have one or you can use the CERNphone app which is described here: <https://cernphone.docs.cern.ch/>. Please make sure that your phone number in SAMS (<https://alice-glance.cern.ch/alice/sams/member/profile?view=permissions>) is correct and that you can receive calls via this number prior to the start of your shift. Technically the requirement for an oncall is that he/she should be able to physically come to P2 within 15 minutes during his/her shift. For PDP it is sufficient if one member of the group is in the local area and can come onsite if necessary. If you as oncall are not in the local area please make sure that someone else is available. So you can also do your shifts completely remotely.


## Meeting duties
**Monday at 4pm:** Software & Computing Meeting (PDP group meeting)\
learn about updates from PDP side which should be communicated to RC during the daily meeting on the following day

**Tuesday at 10.30am** Weekly RC Meeting\
follow information from RC and other central systems, etc

**RC daily meeting at 4.30pm** (except for Mondays, since this overlaps with the PDP group meeting)\
report updates from PDP side and stay informed about what is happening at P2

## Monitoring tools
Some monitoring tools are only available from the CERN GPN, so you might need to configure a SOCKS proxy if you are accessing it from home. You can find documentation on how to set this up at <https://security.web.cern.ch/recommendations/en/ssh_browsing.shtml>. For example if you are using linux you can run a proxy by running inside the terminal\
`ssh -D 8080 lxtunnel.cern.ch -N -l <youruser>`\
Afterwards you can add an extension to your browser (for example FoxyProxy Standard for Firefox) and add a socks5 proxy with the hostname `localhost` and port number `8080`.

Now you can connect to the EPN InfoLogger via:\
<http://alihlt-gw-prod.cern.ch:8081/>

## Expert list
| **What**                    | **Who**           |
|-----------------------------|-------------------|
| Synchronous processing, GPU | David             |
|                             | Ole               |
| EOS, CCDB                   | Latchezar, Costin |
| Calibration                 | Chiara            |
| Reconstruction              | Ruben             |
| Framework                   | Giulio            |

