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

<div>
    <p>ENGN4300 - Hyperview's Repository</p>
    <ul>
      <li><a href="https://docs.google.com/document/d/1hCHGRocxe0S2ev2vEF7xBoG97x4UjUpxqV7dzf2FVTA/edit?usp=drivesdk">README</a></li>
      <li>1.0 Project Management
        <ul>
          <li>1.1 Project Documents
            <ul>
              <li><a href="https://docs.google.com/spreadsheets/d/1DoLDlf2cv8msjHfw7XKHQoi27ekn5HNeHfPoYCiu6Lc/edit?usp=drivesdk">Decision Log</a></li>
              <li><a href="https://docs.google.com/document/d/1B5J7E_MXmqUGW1E5lPnU1Rt51u01Znfv59vZ2n_9y5M/edit?usp=drivesdk">Project Management Plan (PMP) ver2.0</a></li>
              <li><a href="https://docs.google.com/document/d/1tsRHDrZUuc-EVPRS6AfkU_OfzzB_s9dO3NP1C2qho0E/edit?usp=drivesdk">Project Management Plan (PMP) ver1.0</a></li>
              <li>1.1.1 Risk Assessment
                <ul>
                  <li><a href="https://docs.google.com/spreadsheets/d/1hhKzIIcQkVUwMVFiJ6P0BZImEhzJFqPsVsHfVKY5jR8/edit?usp=drivesdk">Risks analysis and tracking for project</a></li>
                  <li><a href="https://docs.google.com/spreadsheets/d/1Xu2dSD1uFWx_H7ZMA9SGeshLFMhArU7yZAS-AGAQKks/edit?usp=drivesdk">Risks analysis for specific operation system</a></li>
                  <li><a href="https://docs.google.com/document/d/1zzqCqEvN-vAhvuENJPSkq5qXA3CLtkoS/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">Risk Management Form</a></li>
                  <li>Previous Risk Assessment from the Host
                    <ul>
                      <li><a href="https://docs.google.com/document/d/1Yg97KhVyP6QDU8QXzxPfKU64gQYU3Pj2/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">Risk Analysis.doc</a></li>
                      <li><a href="https://docs.google.com/document/d/1G35e1JXs-66Vt7dyIdCjSAxVI81_HDDB/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">T2 HS017 Risk Management Form</a></li>
                    </ul>
                  </li>
                </ul>
              </li>
              <li>1.1.2 Timeline and Gantt Chart
                <ul>
                  <li><a href="https://docs.google.com/document/d/1qRMrCeSUsLttpX8CqZRDaRGh2-9gVers/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">Timeline.docx</a></li>
                  <li><a href="https://drive.google.com/file/d/17oXZXmoLi_ml37epCyT2acOigJoxGM2J/view?usp=drivesdk">Gantt chart.pdf</a></li>
                  <li><a href="https://drive.google.com/file/d/1n5Bqqy0M0lejaQ7qbhipWrsni8caM2bf/view?usp=drivesdk">Gantt chart.mpp</a></li>
                </ul>
              </li>
            </ul>
          </li>
        </ul>
      </li>
      <li>2.0 Design and Development
        <ul>
          <li>2.1 Project Initiation
            <ul>
              <li><a href="https://docs.google.com/document/d/1fexxcROwQSZ-jMxOAYUyJ3P4TJYlaPYuo6EW8Nj17Hw/edit?usp=drivesdk">Concept of Operation (version 1.0)</a></li>
              <li><a href="https://docs.google.com/document/d/1KxBFku0A-RBEMFJcSXinIp5gtVe8CJ4kdc5aZJNKutM/edit?usp=drivesdk">Concept of Operation (version 2.0)</a></li>
            </ul>
          </li>
          <li>2.4 Conceptual Design</li>
          <li>2.5 Detailed Design</li>
        </ul>
      </li>
      <li>3.0 Documentation
        <ul>
          <li>3.1 Technical Documents
            <ul>
              <li><a href="https://drive.google.com/file/d/12qawX-7HqQ2FmjvlHYe4rD13MBMGxwYW/view?usp=drivesdk">FillProcedure.pdf</a></li>
              <li><a href="https://drive.google.com/file/d/1uzRJsyl9gmWZRouysaHSo7IKntWssRTX/view?usp=drivesdk">Stalker1967.PDF</a></li>
              <li><a href="https://docs.google.com/document/d/1KAw5eTHZu2KSsvJorcJ0w2BIgBKIEK3jjPRZzBBoExE/edit?usp=drivesdk">FillProcedure (Google Doc)</a></li>
              <li><a href="https://drive.google.com/file/d/1J5Ds7it2wzqGJkJGf61drAfwipLgwobL/view?usp=drivesdk">TADFA operation Ver6 S2.pdf</a></li>
              <li><a href="https://docs.google.com/presentation/d/1f2T3q5OCO97XLYPWtg1jQrrQ-QiRaQTM/edit?usp=drivesdk&ouid=114522111113931296621&rtpof=true&sd=true">TADFA operation Ver6 S2 (PPT)</a></li>
            </ul>
          </li>
          <li>3.2 User Manuals</li>
        </ul>
      </li>
      <li>4.0 Resources
        <ul>
          <li><a href="https://docs.google.com/spreadsheets/d/1oENvKacNgg2l32enPyqJQ6oYBEzuQ9opnA3G8n2iQ8E/edit?usp=drivesdk">Components Tracking Log</a></li>
          <li>4.1 File Templates
            <ul>
              <li><a href="https://drive.google.com/file/d/1_ZotqG8KIPVEIntdQocYxmpisOpl0J1K/view?usp=drivesdk">Weekly Status Report Template.png</a></li>
              <li><a href="https://docs.google.com/document/d/1nvu_AkOsaKER2yw4EOJddKCzZqo-gPc5XcIz2xW_ppY/edit?usp=drivesdk">Meeting Minutes Template</a></li>
              <li>ANU Templates
                <ul>
                  <li><a href="https://drive.google.com/file/d/1DmegN0TzAexU4EODHf1WBI9lElQh7YAg/view?usp=drivesdk">Word-Committee-Minutes Template 2024.dotx</a></li>
                  <li><a href="https://drive.google.com/file/d/1PhDYHvDOTdNGblXU2m05-eEWg4fg1kMB/view?usp=drivesdk">Word-Blank-Letterhead 2023.dotx</a></li>
                </ul>
              </li>
            </ul>
          </li>
          <li>4.3 ANU System Engineering
            <ul>
              <li><a href="https://drive.google.com/file/d/1kc3KOLeWCK1438UVgQZHfWAqwnbR5amg/view?usp=drivesdk">A02 Requirements Mapping.pdf</a></li>
              <li><a href="https://drive.google.com/file/d/1cfTzKEd0Ecobk5-M6BfuuLGVIsk1UdgP/view?usp=drivesdk">A03 Metric Frameworks.pdf</a></li>
            </ul>
          </li>
        </ul>
      </li>
    </ul>
  </div>
