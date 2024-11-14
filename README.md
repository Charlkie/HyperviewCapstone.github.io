# Automation of T2 Free-Piston Shock Tunnel (Shock-driven wind tunnel)

<table>
  <tr>
    <th colspan="4" style="text-align:center;">Project Status Report Template</th>
  </tr>
  <tr>
    <td><strong>Project Name</strong></td>
    <td colspan="3">Project Name</td>
  </tr>
  <tr>
    <td><strong>Date</strong></td>
    <td>Date report created</td>
    <td><strong>Created By</strong></td>
    <td>Name of creator</td>
  </tr>
  <tr>
    <td><strong>Status RAG</strong></td>
    <td><strong><span style="color:red;">&#11044;</span> Time</strong></td>
    <td><strong><span style="color:yellow;">&#11044;</span> Quality</strong></td>
    <td><strong><span style="color:green;">&#11044;</span> Budget</strong></td>
  </tr>
  <tr>
    <td><strong>Progress Last Week</strong></td>
    <td colspan="3">What got done last week along with how this compared against the plan</td>
  </tr>
  <tr>
    <td><strong>To Do This Week</strong></td>
    <td colspan="3">List what is to be done in the coming week.</td>
  </tr>
  <tr>
    <td><strong>New Issues, Risks, Blockers</strong></td>
    <td colspan="3">List any new issues, risks, or blockers you want to raise. Feel free to raise any other project-related issues.</td>
  </tr>
  <tr>
    <td><strong>Update on Issues, Risks, Blockers Raised Last Week</strong></td>
    <td colspan="3">List what has happened to each of the issues, risks, or blockers you raised last week.</td>
  </tr>
</table>

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
please no inserting code lol, no parsing done on input

https://issue-tracker-1d4ed.firebaseapp.com/

## Work Break-Down Structure

https://docs.google.com/spreadsheets/d/121keRA4e_B9DwGpZujkCIpi9Lcfe3kRTRIhdFKdyd7o/edit?gid=0#gid=0

## Repositories
We have all of our documents on google drive and can be viewed(but not edited)
[here](https://drive.google.com/drive/folders/1iQv86kc0_cZ6hoyYyBE39-fbijGRcRPB?usp=sharing).

```ENGN4300 - Hyperview's Repository
  |_ 7.0 Discarded Files
  |_ 6.0 Project Closure
  |_ 5.0 Communications
  |_   |_ 5.2 Meeting Minutes
  |_   |_   |_ Meeting 08
  |_   |_   |_ 23-Aug-24 Meeting 07
  |_   |_   |_ 20-Aug-24 Meeting 05
  |_   |_   |_ 22-Aug-24 Meeting 06
  |_   |_   |_ 19-Aug-24 Meeting 04
  |_   |_   |_ 6-Aug-24 Meeting 02.docx
  |_   |_   |_ 6-Aug-24 Meeting 01.docx
  |_   |_   |_ 12-Aug-24 Meeting 03
  |_   |_ 5.1 Project Audit
  |_   |_   |_ Audit 4
  |_   |_   |_ Audit 3
  |_   |_   |_ Mid-Project Presentation
  |_   |_   |_ Audit 2
  |_   |_   |_ Audit 1
  |_   |_   |_   |_ ConOps with Host's Comments.pdf
  |_   |_   |_   |_ PA1 Feedback Log
  |_   |_   |_   |_ Hyperview_Audit 1_Presentation
  |_   |_   |_   |_ Hyperview_Audit 1_Presentation.potx
  |_ 4.0 Resources
  |_   |_ 4.4 Reference Documents
  |_   |_   |_ Reference Pictures
  |_   |_   |_ ConOps_ProjectVer_2024_V6.pdf
  |_   |_   |_ ketowhistle Concept Of Operations v1.1.pdf
  |_   |_ 4.2 Code Resources
  |_   |_ 4.3 ANU System Engineering
  |_   |_   |_ A04_Functional_Breakdown.pdf
  |_   |_   |_ A03_Metric_Frameworks.pdf
  |_   |_   |_ A02_RequirementsMapping.pdf
  |_   |_ 4.1 File Templates
  |_   |_   |_ ANU Templates
  |_   |_   |_   |_ Word-Blank-Letterhead 2023.dotx
  |_   |_   |_   |_ Word-Committee-Minutes Template 2024.dotx
  |_   |_   |_ Meeting Minutes Template
  |_   |_ Components Tracking Log
  |_ 3.0 Documentation
  |_   |_ 3.2 User Manuals
  |_   |_ 3.1 Technical Documents
  |_   |_   |_ Hardware Specs
  |_   |_   |_ Stalker1967.PDF
  |_   |_   |_ FillProcedure.pdf
  |_ 2.0 Design and Development
  |_   |_ 2.2 Project Planning(Ongoing)
  |_   |_   |_ Work Beakdown Structure(template atm)
  |_   |_   |_ Project Requirements and Responsibility
  |_   |_   |_ Activities Brainstorm
  |_   |_ 2.3 Project Research(Solutions Discovering Phase)
  |_   |_ 2.1 Project Initiation
  |_   |_   |_ Concept of Operation(version 1.0)
  |_   |_   |_ Concept of Operations(Draft)
  |_   |_ 2.5 Detailed Design
  |_   |_ 2.4 Conceptual Design
  |_ 1.0 Project Management
  |_   |_ 1.1 Project Documents
  |_   |_   |_ Decision Log
  |_   |_   |_ Risks analysis for specific operation system
  |_   |_   |_ Risks analysis and tracking for project
  |_   |_   |_ Project Management Plan(PMP)
  |_   |_   |_ Timeline.docx
  |_   |_ gantt chart.mpp
  |_   |_ gantt chart.pdf
  |_ Tickets
  |_ README```
