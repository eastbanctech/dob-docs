---
layout: page
title: Overview of the Dashboard
categories: first release
author: EastBanc Technologies
name: EastBanc Technologies
email: contact@eastbanctech.com
parent: Dispatch Portal
nav_order: 2
---

<section id="overview-of-the-dashboard" markdown="1">

# Overview of the Dashboard

<section id="map-legend" markdown="1">

## Map Legend
After logging in, the default view is the Dashboard with a map that displays the Inspectors' real-time location and the Assignments/Inspections on the map for TODAY only with status Assigned (more on statuses in section [Assignments Filters](#-Assignments-Filter)).

![db1 -screenshot](image/ip-dashboard/dashboard.png)

<section id="boundaries" markdown="1">

### Boundaries
The map displays the DCRA boundaries on the map.

![db1 -screenshot](image/ip-dashboard/dashboard.png)

</section>

<section id="groupings" markdown="1">

### Groupings
When there're two or more inpsections in a certain location, the map displays how many of them are grouped together. Zooming in on the map to that location separates that grouping into individual inspections or assignment groupings as seen on the second screenshot

![db2 -screenshot](image/ip-dashboard/groupings.png)

![db34](image/ip-dashboard/groupings1.png)

When there're two or more Inspectors in a certain location, the map displays how many of them are grouped together. Zooming in on the map separates that grouping into individual inspectors. 

![db3 -screenshot](image/ip-dashboard/groupings2.png)

</section>
</section>

<section id="assignment-card" markdown="1">

## Assignment Card
Clicking on an Inspection number on the map displays a popup called the Assignment card with the following information: Inspection number, Inspection date/time, Inspection type, Inspection address and Inspector assigned.

Clicking through on the Inspection number on the card navigates to Assignment Details page.

![db4 -screenshot](image/ip-dashboard/assignment.png)

![db5 -screenshot](image/ip-dashboard/assignment1.png)

Clicking on Assignment groupings on the map displays a list of Inspection Numbers with their status and clicking on an Inspection number from the list displays Assignment card popup.

![db31 -screenshot](image/ip-dashboard/assignment2.png)

</section>

<section id="inspector-card" markdown="1">

## Inspector Card
Clicking on the Inspector icon on the map displays the Inspector card with the following information: Inspector name, Inspector status, Schedule and Details

![db6 -screenshot](image/ip-dashboard/inspector-card.png)

![db15 -screenshot](image/ip-dashboard/inspector-card1.png)

Clicking through on the Inspector Name, Initials, or Details button on the card navigates to Inspector Details page, as seen in the 2nd screenshot. 

![db16 -screenshot](image/ip-dashboard/inspector-card2.png)

![db8 -screenshot](image/ip-dashboard/inspector-card3.png)
</section>

<section id="filters" markdown="1">

## Filters
To filter out specific Assignments or Inspectors, click on the filter icon.

![db9 -screenshot](image/ip-dashboard/filters.png)

<section id="inspectors-filter" markdown="1">

### Inspectors Filter
Clicking on the filter icon displays the filters menu with RESET TAB and RESET ALL buttons.
   * RESET TAB button: Clicking Reset TAB button will resets all fields to default in the current filter menu
   * RESET ALL button: Clicking Reset All button will resets all fields to default in all three filters menu (Inspectors, Assignments and Clusters) 

![db11 -screenshot](image/ip-dashboard/inspectors-filter.png)

1. To filter for a specific Inspector by name, click on Inspector name and begin typing in the Inspector's name (first or last), and select one of the auto-complete matches from    the list.

2. Selecting All, Internal and External displays the selected Type of Inspector on the map.
   * Internal Inspectors - FTE DCRA employees
   * External Inspectors - Resident Inspectors

3. To filter Inspectors by department, click on Select department and selecting Illegal Construction and/or OIS displays Inspector/s who works for the selected department on the    map.

4. Selecting one, all, or more of Inspector status filters, displays the selected Inspectors with those statuses on the map. The Status of Inspector is a real-time indicator the    Inspector has chosen in their Inspector app on their device.

   * On Duty (orange icon on map) - On Duty for DCRA and the Inspector location is being reported to DCRA
   * In Transit (green icon on map) - On the way to an Assignment/Inspection location
   * Inspecting (green icon on map) - In the middle of conducting an Inspection
</section>

<section id="assignments-filter" markdown="1">

### Assignments Filter
Selecting Assignments from the filter menu bar displays the assignment filter.

![Group 56 -screenshot](image/ip-dashboard/assignments-filter.png)

1. To view only emergency assignments on the map, select the Emergency Inspection checkbox.

2. To filter for a specific Inspection by Inspection Number, click on Enter number and type in the Inpsection Number, then by pressing enter displays the selected Inspection on the map.

3. Selecting All, Initial and Follow Up displays the selected Type of Inspection/Assignment on the map.

4. To filter Inspections by department, click on Select department and selecting Illegal Construction and/or OIS displays Inspections of the selected department on the map.

5. Selecting one, all or more of Assignment status filters, displays the selected Assignments with those statuses on the map. The Assignment status is driven by the actions of the Inspector in the Inspector app or CityGov app, or an authorized Inspections Portal or Accela user. 

   * Assigned - the Inspection has an assigned time/date and Inspector
   * Inspector in Transit - Inspector is in transit to the Assignment/Inspection location
   * Inspection in Progress - Inspector is in the middle of conducting an inspection
   * Completed - Inspector resulted the Inspection in CityGov app
   * Rescheduled - The system processed the request and this Assignment has been rescheduled and a new Assignment with status Assigned has been created
   * Reschedule Requested - Inspector or Portal user requested a reschedule of the Assignment
   * Canceled - Inspector or Portal/Accela user canceled the scheduled Assignment/Inspection

6. To filter Inspections by the Assigned Inspector, click on Enter Inspector's First or Last Name and begin typing in the Inspector's name (first or last), and select one of the auto-complete matches from the list.

7. To filter Inspections by address, click on Enter Assignment Address and type the inspection address, then by pressing enter displays assignment/s with the selected address on the map.
</section>


<section id="clusters-filter" markdown="1">

### Clusters Filter
Selecting Clusters from the filter menu will display the Clusters filter

Selecting a single, more than one, or All button/s from the filter menu displays the Inspections only in the selected cluster/s.

![db14 -screenshot](image/ip-dashboard/clusters-filter.png)

</section>
</section>
</section>

