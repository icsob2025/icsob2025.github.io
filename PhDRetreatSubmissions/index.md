---
layout: importantdates
---

<script>
    function saveFile(url) {
    var filename = url.substring(url.lastIndexOf("/") + 1).split("?")[0];
    var xhr = new XMLHttpRequest();
    xhr.responseType = 'blob';
    xhr.onload = function() {
        var a = document.createElement('a');
        a.href = window.URL.createObjectURL(xhr.response); // xhr.response is a blob
        a.download = filename; // Set the file name.
        a.style.display = 'none';
        document.body.appendChild(a);
        a.click();
        delete a;
    };
    xhr.open('GET', url);
    xhr.send();
    }
</script>
<b style="font-size: 22px" id="CallForResearchPapers">PhD Retreat – Call for Submissions </b>

The ICSOB 2024 PhD Retreat is an exciting one-day event. The retreat is designed to bring together PhD students who work on research related to software-intensive business. The PhD Retreat provides a friendly and constructive environment for PhD students to present their research proposal as well as intermediate results, and to discuss them with experts and other students in the same field.

<hr> 
<b>Program:</b> 
<ul style="list-style: none;">
  <li> 09:30-10:30 - Session I </li>
  <li> 10:30-11:00 - Morning Coffee </li>
  <li> 11:00-12:00 - Session II </li>
  <li> 12:00-13:00 - Lunch </li>
  <li> 13:00-14:00 - Session III </li>
  <li> 14:00-15:00 - Afternoon Coffee</li>
  <li> 15:00-16:00 -  Session IV </li>
  <li> 16:00-16:40 - Two tracks </li>
  <li> 16:40-17:00 -  PhD Retreat Closing </li>
</ul>
<hr>

<b>Target Audience:</b>

PhD students should consider participating in this PhD Retreat if they have already identified a topic to focus their PhD thesis on and have a proposed methodological plan (early-stage PhD students). The PhD Retreat also invites PhD students who are in the mid-stage progress of their thesis (mid-stage PhD students). However, the PhD Retreat is NOT suitable for PhD students at the end of their PhD and who have completed all of their research activities.

The main goals of the PhD Retreat are to provide an opportunity for PhD students to:

<ul style="list-style: none;">
  <li> Interact and exchange ideas with researchers, practitioners and other PhD students in the software-business research community; </li>
  <li> Receive constructive feedback on their current and future research; </li>
  <li> Develop a critical discussion about their work with experts; </li>
  <li> Present their work as a poster at the ICSOB 2024 poster track; </li>
  <li> Build your research network and have fun! </li>
</ul>

The PhD Retreat will take place at a special location: Winkel van Sinkel (address is Oudegracht 158, 3511 AZ Utrecht), which is 600 meters from the Utrecht city center. Therefore, in addition to the technical sessions, the PhD Retreat participants will have the opportunity to explore the tranquility they have to offer.

<hr>
<b style="font-size: 18px" id="SubmissionCategories">Submission Categories</b><br>

We welcome two categories of submission:
<br>
<b>Early-stage PhD submission</b>: This category refers to PhD students who have an initial idea about their research topic and design, and are looking for early feedback on how to proceed with their PhD thesis;
<br>

<b>Mid-stage PhD submission</b>: This category refers to PhD students who have already started the implementation of their research with some preliminary results, and are looking for feedback before completing their PhD thesis.  

<b style="font-size: 18px" id="ImportantDates">Important Dates</b><br>
<p class="lead">
   <p><b>PhD Retreat:</b></p>
    <ul style="list-style: none;">
    <li>Submission Deadline: October 21, 2024 (AoE)</li>
    <li>Notification of Acceptance: October 28, 2024</li>
    <li>Camera-ready Papers Due: December 9, 2024</li>
    <li>Conference Dates: November 19-20, 2024</li>
    </ul>
</p>

<hr>
<b style="font-size: 18px" id="Submissions">Submissions</b><br>
The PhD Retreat submission must consist of two elements:
<br>

A letter from the PhD student’s supervisor. The letter should include the current state of the PhD student’s research as well as the expected date to complete the PhD thesis. The letter should be submitted via email, directed to the PhD Retreat chairs (<a href= "mailto:rps@uniriotec.br" target="_blank">rps@uniriotec.br</a>, <a href= "mailto:dron.khanna@unibz.it" target="_blank">dron.khanna@unibz.it</a>, and <a href= "mailto:e.elshan@vu.nl" target="_blank">e.elshan@vu.nl</a>); and 
<br>

A short paper that describes the PhD student’s thesis. The short paper should not be anonymous and should meet the following requirements:

<br>
<ul style="list-style: none;">
  <li>Be authored only by the student and his/her supervisors;</li>
  <li>Clearly state the problem to be addressed in the student’s thesis, and why this problem is important to be tackled (motivation);</li>
  <li>Discuss related work, and the knowledge gap in the literature that has been addressed in the thesis;</li>
    <li>Describe the research method and the evaluation plan of the results;</li>
    <li>Include the planned timeline for thesis completion;</li>
    <li>Present the results achieved so far (requested for the mid-stage PhD submission only);</li>
    <li>Explain the expected contributions of the thesis.</li>
</ul>

<br>

<br>
To address the items above, we suggest the following structure: Problem Definition, Knowledge Gap, Research Method, Timeline, Preliminary Results (if any), and Expected Contributions. All submissions must be written in English.

<br>
Students interested in participating in the PhD Retreat must submit a short paper (5-9 pages) using the CEUR-ART one-column template which is available here: <a onclick="saveFile('http://ceur-ws.org/Vol-XXX/CEURART.zip')">http://ceur-ws.org/Vol-XXX/CEURART.zip</a>(LaTeX) or <a href="http://ceur-ws.org/Vol-XXX/CEUR-Template-1col.docx" target="_blank">http://ceur-ws.org/Vol-XXX/CEUR-Template-1col.docx</a>(Word). The accepted PhD Retreat submissions will be offered for publication by CEUR-WS.org (open access) in the ICSOB 2024 Companion Proceedings.

<hr>
<b style="font-size: 18px" id="Reviewprocesss">Review Process</b><br>

All submissions will be peer-reviewed by the Program Committee members. The main evaluation criteria are scope, relevance, originality, soundness, accuracy, and clarity. 

<hr>
<b style="font-size: 18px" id="Presentation">Presentation</b><br>

Authors of the accepted submissions will have the opportunity to present their work in the PhD Retreat, and to have camera-ready of their papers published in the post-conference proceedings. The camera-ready versions will be sent after the conference (Deadline: November 20, 2024), so that participants have the chance to polish their papers based on the feedback they got from the conference.
<br>
<br>
Authors will present their research at the conference. Each participant will have 10 to 15 minutes to present plus 10 to 15 minutes for answering questions. There will be networking breaks after blocks of  presentations in which participants can get feedback and comments about their research in a more relaxed Q&A session. After running the presentations, a thesis-design workshop session with experts who will be acting as mentors for the participants during the session is planned.   
<br>
<br>
In addition, authors will be invited to present their work at the poster track of the main conference to get more feedback from the conference attendees. This poster track will be an additional (optional) choice for the PhD Retreat participants, without the need to submit their research to the poster track. 
