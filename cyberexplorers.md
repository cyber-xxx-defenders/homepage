---
layout: blog
title: Cyber Explorers Program
permalink: /cyberexplorers/
---
<h3 class="title">Cyber Explorers Highschool Program</h3>

Cyber Explorers is a 7-week immersive program aimed at introducing Cyber Security discipline to high school and middle school students.
The program doesn’t assume any exposure to computers and computer science. The first 3 sessions are tabletop fun games and exercises 
introducing concepts of Cyber Security like Cryptography, Network Security, Defense in Depth, Incident Detection, Incident Response et al.

The students will start early in the program on a team project which could be a cybersecurity-related puzzle, poster or a project. 
This is a deliverable which students are expected to showcase in the Cyber Explorers finale - which would be attended by parents, 
teachers and potentially rest of the school.

In the latter half of the program after a session on Ethics and signing of a displayable ethics pledge, 
we introduce hands-on exercises and threats which students will replicate in a lab environment. We start the labs with a gentle 
introduction to shell and operating systems and the drop into network security, log analysis and forensics. 

<br/>
<h6 class="subtitle">Program details</h6>
<table class="table is-bordered is-striped">
    <thead>
        <td>Session</td><td>Description</td><td>Notes</td>
    </thead>
    <tbody>
    {% for session in site.data.cyber-explorers-curriculum-program %} 
    <tr>
        <td>{{session.session}}</td>
        <td>{{session.description}}</td>
        <td>{{session.notes}}</td>
    </tr>
    {% endfor %}
    </tbody>
</table>

Through the Cyber Explorers, we aim at having a strong industry partnership using guest lectures, hackathons 
and exposing students to career paths. One of the session labs will be tailored as a Cyber Patriots test - which will 
introduce students to the Cyber Patriots program and other relevant national initiatives. 

The program finale will showcase student work and projects to a broad audience. During the duration of the program, 
we will offer an extensive cybersecurity library and a raspberry pi based project lab environment. We strive to align 
this program to other industry efforts and also offer a  hackathon.