# Automation of T2 Free-Piston Shock Tunnel (Shock-driven wind tunnel)

![Example Shock Tunnel Diagram](./Shock_Tunnel.png)

<div style="text-align: center; font-family: 'Roboto', sans-serif;">
    <h2 style="font-family: 'Roboto', sans-serif; text-decoration: none;">T2 Shock Tunnel Automation Progress</h2>
    <div style="width: 80%; margin: 0 auto; background-color: #f3f3f3; border-radius: 15px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); height: 50px;">
        <div style="height: 100%; width: 30%; background-color: rgb(82, 233, 0); border-radius: 15px; text-align: center; line-height: 50px; color: white; font-weight: bold;">
            30%
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

## [Concept of Operations](https://docs.google.com/document/d/e/2PACX-1vRGPuAjrLsx784MuRp6Z50Rg-7hdHrNgCCaArmJ4hUA0zoNK-3MK4YHsUOnW50Ay2KSNTIYVoVEV5WG/pub)

## [Issue Tracker](https://issue-tracker-1d4ed.firebaseapp.com/)

## [Work Break-Down Structure](https://docs.google.com/spreadsheets/d/121keRA4e_B9DwGpZujkCIpi9Lcfe3kRTRIhdFKdyd7o/edit?gid=0#gid=0)

## [Repositories](https://drive.google.com/drive/folders/1iQv86kc0_cZ6hoyYyBE39-fbijGRcRPB?usp=sharing)

For convenince an expanded view (with link) of the repo's is provided below.

<div>
    <a href="https://drive.google.com/drive/folders/1iQv86kc0_cZ6hoyYyBE39-fbijGRcRPB?usp=sharing">ENGN4300 - Hyperview's Repository</a>
    <ul>
        <li><a href="https://docs.google.com/document/d/1hCHGRocxe0S2ev2vEF7xBoG97x4UjUpxqV7dzf2FVTA/edit?usp=drivesdk">README</a></li>
<li>1.0 Project Management<ul>  <li>1.1 Project Documents<ul>    <li><a href="https://docs.google.com/spreadsheets/d/1DoLDlf2cv8msjHfw7XKHQoi27ekn5HNeHfPoYCiu6Lc/edit?usp=drivesdk">Decision Log</a></li>
    <li><a href="https://docs.google.com/document/d/1B5J7E_MXmqUGW1E5lPnU1Rt51u01Znfv59vZ2n_9y5M/edit?usp=drivesdk">Project Management Plan(PMP)_ver2.0</a></li>
    <li><a href="https://docs.google.com/document/d/1tsRHDrZUuc-EVPRS6AfkU_OfzzB_s9dO3NP1C2qho0E/edit?usp=drivesdk">Project Management Plan(PMP)_ver1.0</a></li>
    <li>1.1.1 Risk Assessment<ul>      <li><a href="https://docs.google.com/spreadsheets/d/1hhKzIIcQkVUwMVFiJ6P0BZImEhzJFqPsVsHfVKY5jR8/edit?usp=drivesdk">Risks analysis and tracking for project</a></li>
      <li><a href="https://docs.google.com/spreadsheets/d/1Xu2dSD1uFWx_H7ZMA9SGeshLFMhArU7yZAS-AGAQKks/edit?usp=drivesdk">Risks analysis for specific operation system</a></li>
      <li><a href="https://docs.google.com/document/d/1zzqCqEvN-vAhvuENJPSkq5qXA3CLtkoS/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">Risk_Management_Form.doc.docx</a></li>
      <li>Previous Risk Assessment from the Host<ul>        <li><a href="https://docs.google.com/document/d/1Yg97KhVyP6QDU8QXzxPfKU64gQYU3Pj2/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">Risk Analysis.doc</a></li>
        <li><a href="https://docs.google.com/document/d/1G35e1JXs-66Vt7dyIdCjSAxVI81_HDDB/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">T2 HS017_Risk_Management_Form.doc</a></li></ul></li></ul></li>
    <li>1.1.2 Timeline and Gantt Chart<ul>      <li><a href="https://docs.google.com/document/d/1qRMrCeSUsLttpX8CqZRDaRGh2-9gVers/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">Timeline.docx</a></li>
      <li><a href="https://drive.google.com/file/d/17oXZXmoLi_ml37epCyT2acOigJoxGM2J/view?usp=drivesdk">Gantt chart.pdf</a></li>
      <li><a href="https://drive.google.com/file/d/1n5Bqqy0M0lejaQ7qbhipWrsni8caM2bf/view?usp=drivesdk">Gantt chart.mpp</a></li></ul></li></ul></li></ul></li>
<li>2.0 Design and Development<ul>  <li>2.4 Conceptual Design<ul></ul></li>
  <li>2.5 Detailed Design<ul></ul></li>
  <li>2.1 Project Initiation<ul>    <li><a href="https://docs.google.com/document/d/1fexxcROwQSZ-jMxOAYUyJ3P4TJYlaPYuo6EW8Nj17Hw/edit?usp=drivesdk">Concept of Operation(version 1.0)</a></li>
    <li><a href="https://docs.google.com/document/d/1KxBFku0A-RBEMFJcSXinIp5gtVe8CJ4kdc5aZJNKutM/edit?usp=drivesdk">Concept of Operation(version 2.0)</a></li></ul></li>
  <li>2.3 Project Research(Solutions Discovering Phase)<ul></ul></li>
  <li>2.2 Project Planning(Ongoing)<ul>    <li><a href="https://docs.google.com/document/d/1Pi1xfXld3AEc2-ZpgKhznISLYQOKTuhWwgWCVg-k1Zk/edit?usp=drivesdk">Activities Brainstorm</a></li>
    <li><a href="https://docs.google.com/document/d/1RKCEIU7oSXlYRRzg2-5HSl4U7DWZojl7g0cQCAzH_l8/edit?usp=drivesdk">Project Requirements and Responsibility</a></li>
    <li><a href="https://docs.google.com/document/d/1qaDv8JH0jJA1aq2l--t7euzHxwvO3ihyQluT5ZP--GU/edit?usp=drivesdk">Link to Miro Board - State Machine</a></li>
    <li><a href="https://docs.google.com/spreadsheets/d/121keRA4e_B9DwGpZujkCIpi9Lcfe3kRTRIhdFKdyd7o/edit?usp=drivesdk">Work Beakdown Structure(template atm)</a></li>
    <li><a href="https://docs.google.com/document/d/1nQFc2ksuy0ICWgTy5lAYgYARRynQwWQBbD60VIhYolc/edit?usp=drivesdk">Bill of Material(BoM)</a></li></ul></li></ul></li>
<li>3.0 Documentation<ul>  <li>3.1 Technical Documents<ul>    <li><a href="https://drive.google.com/file/d/12qawX-7HqQ2FmjvlHYe4rD13MBMGxwYW/view?usp=drivesdk">FillProcedure.pdf</a></li>
    <li><a href="https://drive.google.com/file/d/1uzRJsyl9gmWZRouysaHSo7IKntWssRTX/view?usp=drivesdk">Stalker1967.PDF</a></li>
    <li><a href="https://docs.google.com/document/d/1KAw5eTHZu2KSsvJorcJ0w2BIgBKIEK3jjPRZzBBoExE/edit?usp=drivesdk">FillProcedure</a></li>
    <li><a href="https://drive.google.com/file/d/1J5Ds7it2wzqGJkJGf61drAfwipLgwobL/view?usp=drivesdk">TADFA operation Ver6 S2.pdf</a></li>
    <li><a href="https://docs.google.com/presentation/d/1f2T3q5OCO97XLYPWtg1jQrrQ-QiRaQTM/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">TADFA operation Ver6 S2.ppt</a></li>
    <li><a href="https://drive.google.com/file/d/1l15BUDIH_UUrcdguiej6Cx8UZxE7k6g3/view?usp=drivesdk">TADFA operation_ver5.pdf</a></li>
    <li><a href="https://docs.google.com/document/d/1HZ7PBsx7Td6dS_7TdliUDFsRvgFXl9NIDGKd97w5O3g/edit?usp=drivesdk">Hardware Specs</a></li></ul></li>
  <li>3.2 User Manuals<ul></ul></li></ul></li>
<li>4.0 Resources<ul>  <li><a href="https://docs.google.com/spreadsheets/d/1oENvKacNgg2l32enPyqJQ6oYBEzuQ9opnA3G8n2iQ8E/edit?usp=drivesdk">Components Tracking Log</a></li>
  <li>4.1 File Templates<ul>    <li><a href="https://drive.google.com/file/d/1_ZotqG8KIPVEIntdQocYxmpisOpl0J1K/view?usp=drivesdk">Weekly Status Report Template.png</a></li>
    <li><a href="https://docs.google.com/document/d/1nvu_AkOsaKER2yw4EOJddKCzZqo-gPc5XcIz2xW_ppY/edit?usp=drivesdk">Meeting Minutes Template</a></li>
    <li>ANU Templates<ul>      <li><a href="https://drive.google.com/file/d/1DmegN0TzAexU4EODHf1WBI9lElQh7YAg/view?usp=drivesdk">Word-Committee-Minutes Template 2024.dotx</a></li>
      <li><a href="https://drive.google.com/file/d/1PhDYHvDOTdNGblXU2m05-eEWg4fg1kMB/view?usp=drivesdk">Word-Blank-Letterhead 2023.dotx</a></li></ul></li></ul></li>
  <li>4.3 ANU System Engineering<ul>    <li><a href="https://drive.google.com/file/d/1kc3KOLeWCK1438UVgQZHfWAqwnbR5amg/view?usp=drivesdk">A02_RequirementsMapping.pdf</a></li>
    <li><a href="https://drive.google.com/file/d/1cfTzKEd0Ecobk5-M6BfuuLGVIsk1UdgP/view?usp=drivesdk">A03_Metric_Frameworks.pdf</a></li>
    <li><a href="https://drive.google.com/file/d/1M165RC6yTPG9LyF27WJ5iL8Gj6mhLiE6/view?usp=drivesdk">A04_Functional_Breakdown.pdf</a></li></ul></li>
  <li>4.2 Code Resources<ul></ul></li>
  <li>4.4 Reference Documents<ul>    <li><a href="https://drive.google.com/file/d/1t1XXOq4-H2E8eDgQrJvxqXoTUKQl14uT/view?usp=drivesdk">ketowhistle Concept Of Operations v1.1.pdf</a></li>
    <li><a href="https://drive.google.com/file/d/1AIy6S2r2DcEnPd9b4RZrdhqsr2TKZsQn/view?usp=drivesdk">ConOps_ProjectVer_2024_V6.pdf</a></li>
    <li><a href="https://docs.google.com/document/d/1trFy8yDhFH26hs2ZgJUkXp2J-l4gF9ZxRMRtmS7b4mc/edit?usp=drivesdk">Reference Pictures</a></li>
    <li><a href="https://docs.google.com/document/d/1R7NnGUt09i7K-NLl9anz9er1NZLIkhIQK3c6NVI1ev8/edit?usp=drivesdk">work breakdown list</a></li></ul></li></ul></li>
<li>5.0 Communications<ul>  <li>5.1 Project Audit<ul>    <li>Audit 1<ul>      <li><a href="https://drive.google.com/file/d/1tCvlvSC9d0pZ-go7A3-tArFGz_6w8kpA/view?usp=drivesdk">Hyperview_Audit 1_Presentation.potx</a></li>
      <li><a href="https://docs.google.com/presentation/d/1o332-DBdNWfN8MKekMuCF_E1Qq_njO7P0wMe1m5gH_I/edit?usp=drivesdk">Hyperview_Audit 1_Presentation</a></li>
      <li><a href="https://docs.google.com/spreadsheets/d/1eDisrkI9LiXVtiEMfqFzpmXAmHQG_L6stVzzsuRLQs4/edit?usp=drivesdk">PA1 Feedback Log</a></li>
      <li><a href="https://drive.google.com/file/d/1ybLfmy2Xk_7zgYWFiUFsZ56d-H14QaRz/view?usp=drivesdk">ConOps with Host's Comments.pdf</a></li></ul></li>
    <li>Audit 2<ul></ul></li>
    <li>Mid-Project Presentation<ul></ul></li>
    <li>Audit 3<ul></ul></li>
    <li>Audit 4<ul></ul></li></ul></li>
  <li>5.2 Meeting Minutes<ul>    <li><a href="https://docs.google.com/document/d/17njA9AzPTBx2ggsNUffyR_oFYjGoWV_mmm7AOCU9Q3I/edit?usp=drivesdk">12-Aug-24 Meeting 03</a></li>
    <li><a href="https://docs.google.com/document/d/1xk1fioBENHqPZCN84SsiH3FTNyAZ21XA/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">6-Aug-24 Meeting 01.docx</a></li>
    <li><a href="https://docs.google.com/document/d/1OuSagHvfXSSFy4-4zxQAOn-FE0yfP_9D/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">6-Aug-24 Meeting 02.docx</a></li>
    <li><a href="https://docs.google.com/document/d/1cy-97s2ckTCbz8M5DkbDRi4E_N6izAVi7KgQEUpHevQ/edit?usp=drivesdk">19-Aug-24 Meeting 04</a></li>
    <li><a href="https://docs.google.com/document/d/1FFQBYrhzjFoQU7_X3uNytPksYcwBhwKtIHLJPvNJGL4/edit?usp=drivesdk">20-Aug-24 Meeting 05</a></li>
    <li><a href="https://docs.google.com/document/d/164tNkCGfubZwipiL5r37DAnZAOQpA1f8gr0TzJqw4l4/edit?usp=drivesdk">23-Aug-24 Meeting 07</a></li>
    <li><a href="https://docs.google.com/document/d/1umVL5HS3qtZq6PBhnhDIoIe0PC3174S7UZyhJbKR43U/edit?usp=drivesdk">22-Aug-24 Meeting 06</a></li>
    <li><a href="https://docs.google.com/document/d/13ZRdX1BFRRG9riimSK77iJPgOxFzXZtBSpx_H_4MUMY/edit?usp=drivesdk">27-Aug-24 Meeting 08</a></li>
    <li><a href="https://docs.google.com/document/d/16z2I4vIAFuarJnJrAedI_ojqfwl_u_rX6Iv9ig5BOys/edit?usp=drivesdk">17-Sep-24 Meeting 09</a></li>
    <li><a href="https://docs.google.com/document/d/1fUn7TCB4me9H0y9moN7l7OVPqJzYRnxThVrQUOzTWig/edit?usp=drivesdk">20-Sep Meeting 10</a></li>
    <li><a href="https://docs.google.com/document/d/1G1rNSlUH0Gl2jz5zw5Gu49RJNWdW9V9HLQlYiaqLY0I/edit?usp=drivesdk">24-Sep-24 Meeting 11</a></li></ul></li>
  <li>5.3 Weekly Status Report<ul>    <li><a href="https://docs.google.com/spreadsheets/d/1Ig_ibKTQgw9twbmYqQBjc5KxuycQ8t3W86viivgH85c/edit?usp=drivesdk">Weekly Status Report Template</a></li>
    <li><a href="https://docs.google.com/spreadsheets/d/1oo_37hemdeUfv5UChiElpMLGDH5peQOIj8wE4LvaLMo/edit?usp=drivesdk">300824_Week 6 Status Report</a></li></ul></li></ul></li>
<li>6.0 Project Closure<ul></ul></li>
<li>7.0 Discarded Files<ul>  <li><a href="https://docs.google.com/document/d/1r3uWkNP1suAAwSqLf7skwgR-jA6sfGwHxqy84MLwFwU/edit?usp=drivesdk">Concept of Operations(Draft)</a></li>
  <li><a href="https://docs.google.com/spreadsheets/d/16vpW3SHvM3Bb1HX9hGyHoNlPsY_614Sim553lxPsuj0/edit?usp=drivesdk">Tickets</a></li></ul></li>
      </ul>
  </div>
