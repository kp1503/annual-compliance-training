## Overview

This repository contains a simulated employee compliance-training webpage developed for the Georgia Tech PUBP-6725-OCY Go Phish assignment.

The webpage was created solely for an authorized educational social-engineering exercise. It demonstrates how familiarity with an existing professional workflow and website design can influence user trust.

The project is not an official Georgia Tech website and is not intended for use outside the scope of the course assignment.

---

## Purpose

The purpose of the simulation is to demonstrate a spear-phishing scenario based on a familiar employee compliance-training workflow.

The landing page continues the training scenario introduced in the simulated email and demonstrates how a user might respond to an identity-verification request presented within a familiar-looking training interface.

The simulation does **not** request passwords, Duo/MFA codes, recovery codes, financial information, or authentication credentials.

---

## Design Reference

The general visual organization of the simulated training dashboard was informed by the Georgia Tech employee Learner Dashboard:

**Georgia Tech Training Portal**  
`https://gatech.geniussis.com/LearnerDashboard.aspx`

Elements used as general design references include:

- Sidebar navigation
- Training dashboard organization
- Active Courses
- Completed Courses
- Pending Courses
- Learning Paths
- Training status information
- General institutional training-page structure

The simulation is independently developed and is not affiliated with or operated by the Georgia Institute of Technology.

---

## Technical Implementation

The landing page is implemented as a static website using:

- HTML
- CSS
- JavaScript
- GitHub Pages
- HTTPS
- 
## Identity Verification Simulation

As part of the exercise, the page presents an identity-verification interaction requesting:

- Last Name
- 9-digit Georgia Tech ID (GTID)

JavaScript performs basic client-side validation of the fields.

The entered values are used only to demonstrate the interaction and are cleared after the user continues.

---

## Data Handling

This project was designed so that information entered into the simulation is **not retained**.

The webpage does not intentionally:

- Submit the entered information to a server
- Store the information in a database
- Save the information using `localStorage`
- Save the information using cookies
- Retain the entered Last Name or GTID after the interaction

The values are handled within the browser and cleared after the simulated verification step.

After the interaction, the webpage informs the participant that the interaction was part of the PUBP-6725 Go Phish assignment.
