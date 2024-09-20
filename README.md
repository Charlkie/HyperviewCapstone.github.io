# Automation of T2 Free-Piston Shock Tunnel (Shock-driven wind tunnel)

<div style="text-align: center; font-family: 'Roboto', sans-serif;">
    <h2 style="font-family: 'Roboto', sans-serif; text-decoration: none;">T2 Shock Tunnel Automation Progress</h2>
    <div style="width: 80%; margin: 0 auto; background-color: #f3f3f3; border-radius: 15px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); height: 50px;">
        <div style="height: 100%; width: 20%; background-color: orange; border-radius: 15px; text-align: center; line-height: 50px; color: white; font-weight: bold;">
            15%
        </div>
    </div>
</div>

## Project Summary

We are recommissioning a hypersonic research facility at ANU. The T2 shock tunnel facility is old, and manually
controlled. This project involves designing and implementing an automated gas filling system for the T2 shock
tunnel that monitors and performs filling of the various chambers of the facility with gas at specified conditions,
while checking for malfunctions such as leaks and preventing operations from being performed in the wrong
order. This system will be controlled by an ARM-based linux board. The project involves electronic design and
embedded system programming, as well as safety engineering. The output should be a set of open-source codes,
hardware and documentation for a user-friendly interface for this facility.

## Meet the team

- Armando Castelo <u7231943@anu.edu.au>
- Charl Kruger <u6951533@anu.edu.au>
- Kexiang Wang <u7394240@anu.edu.au>
- Maximilian Parker <u7398910@anu.edu.au>
- Xin Lou <u6803896@anu.edu.au>
- Yingzheng Liu <u7112372@anu.edu.au>

## Concept of Operations

The link to our Con-ops can be found here:
[Con-ops](https://docs.google.com/document/d/e/2PACX-1vRGPuAjrLsx784MuRp6Z50Rg-7hdHrNgCCaArmJ4hUA0zoNK-3MK4YHsUOnW50Ay2KSNTIYVoVEV5WG/pub).

## Issue Tracker
Issue tracker]please no inserting code lol, no parsing done on input. Access [here](https://issue-tracker-1d4ed.firebaseapp.com/)

https://issue-tracker-1d4ed.firebaseapp.com/

## Work Break-Down Structure

[WBS](https://docs.google.com/spreadsheets/d/121keRA4e_B9DwGpZujkCIpi9Lcfe3kRTRIhdFKdyd7o/edit?gid=0#gid=0)

## Repositories
We have all of our documents on google drive and can be viewed(but not edited)
[here](https://drive.google.com/drive/folders/1iQv86kc0_cZ6hoyYyBE39-fbijGRcRPB?usp=sharing).

```txt
ENGN4300 - Hyperview's Repository
  |_ [README](https://docs.google.com/document/d/1hCHGRocxe0S2ev2vEF7xBoG97x4UjUpxqV7dzf2FVTA/edit?usp=drivesdk)
  |_ 1.0 Project Management
  |_   |_ 1.1 Project Documents
  |_   |_   |_ [Decision Log](https://docs.google.com/spreadsheets/d/1DoLDlf2cv8msjHfw7XKHQoi27ekn5HNeHfPoYCiu6Lc/edit?usp=drivesdk)
  |_   |_   |_ [Project Management Plan(PMP)_ver2.0](https://docs.google.com/document/d/1B5J7E_MXmqUGW1E5lPnU1Rt51u01Znfv59vZ2n_9y5M/edit?usp=drivesdk)
  |_   |_   |_ [Project Management Plan(PMP)_ver1.0](https://docs.google.com/document/d/1tsRHDrZUuc-EVPRS6AfkU_OfzzB_s9dO3NP1C2qho0E/edit?usp=drivesdk)
  |_   |_   |_ 1.1.1 Risk Assessment
  |_   |_   |_   |_ [Risks analysis and tracking for project](https://docs.google.com/spreadsheets/d/1hhKzIIcQkVUwMVFiJ6P0BZImEhzJFqPsVsHfVKY5jR8/edit?usp=drivesdk)
  |_   |_   |_   |_ [Risks analysis for specific operation system](https://docs.google.com/spreadsheets/d/1Xu2dSD1uFWx_H7ZMA9SGeshLFMhArU7yZAS-AGAQKks/edit?usp=drivesdk)
  |_   |_   |_   |_ [Risk_Management_Form.doc.docx](https://docs.google.com/document/d/1zzqCqEvN-vAhvuENJPSkq5qXA3CLtkoS/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true)
  |_   |_   |_   |_ Previous Risk Assessment from the Host
  |_   |_   |_   |_   |_ [Risk Analysis.doc](https://docs.google.com/document/d/1Yg97KhVyP6QDU8QXzxPfKU64gQYU3Pj2/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true)
  |_   |_   |_   |_   |_ [T2 HS017_Risk_Management_Form.doc](https://docs.google.com/document/d/1G35e1JXs-66Vt7dyIdCjSAxVI81_HDDB/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true)
  |_   |_   |_ 1.1.2 Timeline and Gantt Chart
  |_   |_   |_   |_ [Timeline.docx](https://docs.google.com/document/d/1qRMrCeSUsLttpX8CqZRDaRGh2-9gVers/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true)
  |_   |_   |_   |_ [Gantt chart.pdf](https://drive.google.com/file/d/17oXZXmoLi_ml37epCyT2acOigJoxGM2J/view?usp=drivesdk)
  |_   |_   |_   |_ [Gantt chart.mpp](https://drive.google.com/file/d/1n5Bqqy0M0lejaQ7qbhipWrsni8caM2bf/view?usp=drivesdk)
  |_ 2.0 Design and Development
  |_   |_ 2.4 Conceptual Design
  |_   |_ 2.5 Detailed Design
  |_   |_ 2.1 Project Initiation
  |_   |_   |_ [Concept of Operation(version 1.0)](https://docs.google.com/document/d/1fexxcROwQSZ-jMxOAYUyJ3P4TJYlaPYuo6EW8Nj17Hw/edit?usp=drivesdk)
  |_   |_   |_ [Concept of Operation(version 2.0)](https://docs.google.com/document/d/1KxBFku0A-RBEMFJcSXinIp5gtVe8CJ4kdc5aZJNKutM/edit?usp=drivesdk)
  |_   |_ 2.3 Project Research(Solutions Discovering Phase)
  |_   |_ 2.2 Project Planning(Ongoing)
  |_   |_   |_ [Activities Brainstorm](https://docs.google.com/document/d/1Pi1xfXld3AEc2-ZpgKhznISLYQOKTuhWwgWCVg-k1Zk/edit?usp=drivesdk)
  |_   |_   |_ [Project Requirements and Responsibility](https://docs.google.com/document/d/1RKCEIU7oSXlYRRzg2-5HSl4U7DWZojl7g0cQCAzH_l8/edit?usp=drivesdk)
  |_   |_   |_ [Work Beakdown Structure(template atm)](https://docs.google.com/spreadsheets/d/121keRA4e_B9DwGpZujkCIpi9Lcfe3kRTRIhdFKdyd7o/edit?usp=drivesdk)
  |_   |_   |_ [Bill of Material(BoM)](https://docs.google.com/document/d/1nQFc2ksuy0ICWgTy5lAYgYARRynQwWQBbD60VIhYolc/edit?usp=drivesdk)
  |_ 3.0 Documentation
  |_   |_ 3.1 Technical Documents
  |_   |_   |_ [FillProcedure.pdf](https://drive.google.com/file/d/12qawX-7HqQ2FmjvlHYe4rD13MBMGxwYW/view?usp=drivesdk)
  |_   |_   |_ [Stalker1967.PDF](https://drive.google.com/file/d/1uzRJsyl9gmWZRouysaHSo7IKntWssRTX/view?usp=drivesdk)
  |_   |_   |_ [FillProcedure](https://docs.google.com/document/d/1KAw5eTHZu2KSsvJorcJ0w2BIgBKIEK3jjPRZzBBoExE/edit?usp=drivesdk)
  |_   |_   |_ [TADFA operation Ver6 S2.pdf](https://drive.google.com/file/d/1J5Ds7it2wzqGJkJGf61drAfwipLgwobL/view?usp=drivesdk)
  |_   |_   |_ [TADFA operation Ver6 S2.ppt](https://docs.google.com/presentation/d/1f2T3q5OCO97XLYPWtg1jQrrQ-QiRaQTM/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true)
  |_   |_   |_ [TADFA operation_ver5.pdf](https://drive.google.com/file/d/1l15BUDIH_UUrcdguiej6Cx8UZxE7k6g3/view?usp=drivesdk)
  |_   |_   |_ [Hardware Specs](https://docs.google.com/document/d/1HZ7PBsx7Td6dS_7TdliUDFsRvgFXl9NIDGKd97w5O3g/edit?usp=drivesdk)
  |_   |_ 3.2 User Manuals
  |_ 4.0 Resources
  |_   |_ [Components Tracking Log](https://docs.google.com/spreadsheets/d/1oENvKacNgg2l32enPyqJQ6oYBEzuQ9opnA3G8n2iQ8E/edit?usp=drivesdk)
  |_   |_ 4.1 File Templates
  |_   |_   |_ [Weekly Status Report Template.png](https://drive.google.com/file/d/1_ZotqG8KIPVEIntdQocYxmpisOpl0J1K/view?usp=drivesdk)
  |_   |_   |_ [Meeting Minutes Template](https://docs.google.com/document/d/1nvu_AkOsaKER2yw4EOJddKCzZqo-gPc5XcIz2xW_ppY/edit?usp=drivesdk)
  |_   |_   |_ ANU Templates
  |_   |_   |_   |_ [Word-Committee-Minutes Template 2024.dotx](https://drive.google.com/file/d/1DmegN0TzAexU4EODHf1WBI9lElQh7YAg/view?usp=drivesdk)
  |_   |_   |_   |_ [Word-Blank-Letterhead 2023.dotx](https://drive.google.com/file/d/1PhDYHvDOTdNGblXU2m05-eEWg4fg1kMB/view?usp=drivesdk)
  |_   |_ 4.3 ANU System Engineering
  |_   |_   |_ [A02_RequirementsMapping.pdf](https://drive.google.com/file/d/1kc3KOLeWCK1438UVgQZHfWAqwnbR5amg/view?usp=drivesdk)
  |_   |_   |_ [A03_Metric_Frameworks.pdf](https://drive.google.com/file/d/1cfTzKEd0Ecobk5-M6BfuuLGVIsk1UdgP/view?usp=drivesdk)
  |_   |_   |_ [A04_Functional_Breakdown.pdf](https://drive.google.com/file/d/1M165RC6yTPG9LyF27WJ5iL8Gj6mhLiE6/view?usp=drivesdk)
  |_   |_ 4.2 Code Resources
  |_   |_ 4.4 Reference Documents
  |_   |_   |_ [ketowhistle Concept Of Operations v1.1.pdf](https://drive.google.com/file/d/1t1XXOq4-H2E8eDgQrJvxqXoTUKQl14uT/view?usp=drivesdk)
  |_   |_   |_ [ConOps_ProjectVer_2024_V6.pdf](https://drive.google.com/file/d/1AIy6S2r2DcEnPd9b4RZrdhqsr2TKZsQn/view?usp=drivesdk)
  |_   |_   |_ [Reference Pictures](https://docs.google.com/document/d/1trFy8yDhFH26hs2ZgJUkXp2J-l4gF9ZxRMRtmS7b4mc/edit?usp=drivesdk)
  |_   |_   |_ [work breakdown list](https://docs.google.com/document/d/1R7NnGUt09i7K-NLl9anz9er1NZLIkhIQK3c6NVI1ev8/edit?usp=drivesdk)
  |_ 5.0 Communications
  |_   |_ 5.1 Project Audit
  |_   |_   |_ Audit 1
  |_   |_   |_   |_ [Hyperview_Audit 1_Presentation.potx](https://drive.google.com/file/d/1tCvlvSC9d0pZ-go7A3-tArFGz_6w8kpA/view?usp=drivesdk)
  |_   |_   |_   |_ [Hyperview_Audit 1_Presentation](https://docs.google.com/presentation/d/1o332-DBdNWfN8MKekMuCF_E1Qq_njO7P0wMe1m5gH_I/edit?usp=drivesdk)
  |_   |_   |_   |_ [PA1 Feedback Log](https://docs.google.com/spreadsheets/d/1eDisrkI9LiXVtiEMfqFzpmXAmHQG_L6stVzzsuRLQs4/edit?usp=drivesdk)
  |_   |_   |_   |_ [ConOps with Host's Comments.pdf](https://drive.google.com/file/d/1ybLfmy2Xk_7zgYWFiUFsZ56d-H14QaRz/view?usp=drivesdk)
  |_   |_   |_ Audit 2
  |_   |_   |_ Mid-Project Presentation
  |_   |_   |_ Audit 3
  |_   |_   |_ Audit 4
  |_   |_ 5.2 Meeting Minutes
  |_   |_   |_ [12-Aug-24 Meeting 03](https://docs.google.com/document/d/17njA9AzPTBx2ggsNUffyR_oFYjGoWV_mmm7AOCU9Q3I/edit?usp=drivesdk)
  |_   |_   |_ [6-Aug-24 Meeting 01.docx](https://docs.google.com/document/d/1xk1fioBENHqPZCN84SsiH3FTNyAZ21XA/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true)
  |_   |_   |_ [6-Aug-24 Meeting 02.docx](https://docs.google.com/document/d/1OuSagHvfXSSFy4-4zxQAOn-FE0yfP_9D/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true)
  |_   |_   |_ [19-Aug-24 Meeting 04](https://docs.google.com/document/d/1cy-97s2ckTCbz8M5DkbDRi4E_N6izAVi7KgQEUpHevQ/edit?usp=drivesdk)
  |_   |_   |_ [20-Aug-24 Meeting 05](https://docs.google.com/document/d/1FFQBYrhzjFoQU7_X3uNytPksYcwBhwKtIHLJPvNJGL4/edit?usp=drivesdk)
  |_   |_   |_ [23-Aug-24 Meeting 07](https://docs.google.com/document/d/164tNkCGfubZwipiL5r37DAnZAOQpA1f8gr0TzJqw4l4/edit?usp=drivesdk)
  |_   |_   |_ [22-Aug-24 Meeting 06](https://docs.google.com/document/d/1umVL5HS3qtZq6PBhnhDIoIe0PC3174S7UZyhJbKR43U/edit?usp=drivesdk)
  |_   |_   |_ [27-Aug-24 Meeting 08](https://docs.google.com/document/d/13ZRdX1BFRRG9riimSK77iJPgOxFzXZtBSpx_H_4MUMY/edit?usp=drivesdk)
  |_   |_   |_ [17-Sep-24 Meeting 09](https://docs.google.com/document/d/16z2I4vIAFuarJnJrAedI_ojqfwl_u_rX6Iv9ig5BOys/edit?)
```
