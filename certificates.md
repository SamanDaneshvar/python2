---
layout: page
title: Certificates
subTitle: Python ASAP
sitemap: false
---
# Verify a certificate

<h3>Search by certificate number</h3>
<label for="query_cert">Certificate number:</label>
<input id="query_cert" placeholder="1801-1111"/>
<button id="search_by_cert_button">Search</button>

---

<h3>Search by name and date of birth</h3>
<label for="query_first_name">First name:</label>
<input id="query_first_name" placeholder="John" />
<label for="query_last_name">Last name:</label>
<input id="query_last_name" placeholder="Smith" />
<button id="search_by_name_button">Search</button>

<h3>Participant's Certificates</h3>
<div id="list_of_certificates"></div>

---

<h3>Certificate Details</h3>

&nbsp;                                | &nbsp;
:-                                    | :-
Participant's Legal Name:&nbsp;&nbsp; | <span id="first_name" /> <span id="last_name" />
Total Certificates:                   | <span id="total_certificates" />
Certificate Number:                   | <span id="certificate_number" />
Date Issued:                          | <span id="date_of_issue" />
Status:                               | <span id="status" />
Course Name:                          | <span id="course_name" />
Course Length:                        | <span id="course_length" />
Curriculum:                           | <a href="" id="course_curriculum"></a>
Grade:                                | <a href="" id="certification_grade"></a>
Achievability:                        | <span id="achievability" />



<!-- Insert these scripts at the bottom of the HTML, but before you use any Firebase services -->
<!-- Firebase App (the core Firebase SDK) is always required and must be listed first -->
<script defer src="https://www.gstatic.com/firebasejs/8.1.2/firebase-app.js"></script>
<!-- If you enabled Analytics in your project, add the Firebase SDK for Analytics -->
<script defer src="https://www.gstatic.com/firebasejs/8.1.2/firebase-analytics.js"></script>
<!-- Add any other Firebase products that you want to use -->
<script defer src="https://www.gstatic.com/firebasejs/8.1.2/firebase-auth.js"></script>
<script defer src="https://www.gstatic.com/firebasejs/8.1.2/firebase-firestore.js"></script>

<!-- Make sure Firebase SDKs are loaded before this -->
<script defer src="{{ site.url }}/assets/js/verify-certificates.js"></script>














<!--
| Legal Name | Certificate Code |
| :- | :- |
| John Smith | 2012-0486 |
| Jane Black | 2012-7362 |

&nbsp; | &nbsp;
:- | :-
**Participant's Legal Name** | John Smith
**Certificate Number** | 2012-0486
**Date Issued** | December 5, 2020
**Status** | Valid
**Course Name** | Zero to Intermediate Python Programming
**Course Length** | 18 hours
**Curriculum** | [Z2I Python]()
**Grade** | [Certificate of Participation]()
**Achievability** | 12/12


## Did not find the certificate you were trying to verify?
[Request an official confirmation]() or [report a false claim]().

## Did not find your own certificate?
[Report an issue with the database]() (e.g., false or missing information).

Rest assured that at Saman Daneshvar's Coding Academy records don't go missing! If you have successfully completed a course, you are entitled to a certificate.
-->
