---
layout: importantdates
---

<style>
#registration {
  font-family: Arial, Helvetica, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

#registration td, #registration th {
  border: 1px solid #ddd;
  padding: 8px;
}

#registration tr:nth-child(even){background-color: #f2f2f2;}

#registration tr:hover {background-color: #ddd;}

#registration th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #000;
  color: white;
}

    /* Styling for the button */
    .styled-button {
      background-color: #000; /* Green background */
      border: none; /* Remove border */
      color: white; /* White text */
      padding: 15px 32px; /* Padding */
      text-align: center; /* Center text */
      text-decoration: none; /* Remove underline */
      display: inline-block; /* Inline block display */
      font-size: 16px; /* Font size */
      margin: 4px 2px; /* Margin */
      cursor: pointer; /* Pointer cursor */
      border-radius: 8px; /* Rounded corners */
      transition: background-color 0.3s ease; /* Smooth background color transition */
    }

    /* Hover effect */
    .styled-button:hover {
      background-color: #45a049; /* Darker green background on hover */
    }
  </style>

  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <script>
    let redirectUrl = '';

    function setRedirectUrl(url) {
      redirectUrl = url;
    }

    function redirectToSelected() {
      if (redirectUrl !== '') {
        window.location.href = redirectUrl;
      } else {
        alert('Please select a radio button first.');
      }
    }
  </script>

<div class="col-lg8 mx-auto">
    <h1 class="display-4" style="text-align: left;">
        Registration
    </h1>
    <p> Registration and payments for the ICSOB 2024 conference should be completed via the online registration system. Registration is required for all persons attending the conference.</p>

<p> Registration fees:</p>
<p>
 <table id="registration">
  <tr>
    <th>Categories</th>
    <th>Early Bird Registration Fee (till October 23rd)</th>
    <th>Standard Registration Fee (from October 24th)</th>
  </tr>
  <tr>
    <td>Student, Full conference</td>
    <td> <label>
      <!--<input type="radio" name="redirectOption" disabled > € 600.00 </label> </td>-->
    
       <input type="radio" name="redirectOption" onclick="setRedirectUrl('https://uusalesservices.uu.nl/international-conference-software-business-phd-student-october-23rd')" /> € 600.00 </label> </td>
    <td> <label>
    <input type="radio" name="redirectOption" disabled > € 700.00 </label> </td>
      <!--<input type="radio" name="redirectOption" onclick="setRedirectUrl('https://uusalesservices.uu.nl/international-conference-software-business-phd-student-after-october-1st')" /> € 700.00 </label> </td>-->

  </tr>
  <tr>
    <td>Regular, Full conference</td>
    <td> <label>
    <!-- <input type="radio" name="redirectOption" disabled > € 700.00 </label> </td> -->
      <input type="radio" name="redirectOption" onclick="setRedirectUrl('https://uusalesservices.uu.nl/international-conference-software-business-regular-attendance-october-23rd')" /> € 700.00 </label> </td>
    <td> <label>
    <input type="radio" name="redirectOption" disabled > € 800.00 </label> </td>
 <!-- <input type="radio" name="redirectOption" onclick="setRedirectUrl('https://uusalesservices.uu.nl/international-conference-software-business-regular-attendance-registration-after-october-1st')" /> € 800.00 </label> </td> -->
    
  </tr>
   
  <tr>
    <td>Student, Full conference + PhD Retreat (if accepted) </td>
    <td> <label>
      <input type="radio" name="redirectOption" onclick="setRedirectUrl('https://uusalesservices.uu.nl/international-conference-software-business-phd-student-october-1st-retreat-combo')" /> € 500.00 </label> </td>
    
   <td></td>
  </tr>

  <tr>
    <td>Student, only PhD retreat</td>
    <td> <label>
      <input type="radio" name="redirectOption" onclick="setRedirectUrl('https://uusalesservices.uu.nl/international-conference-software-business-student-october-1st-phd-retreat-only')" /> € 200.00 </label> </td>
    
    <td></td>
  </tr>

    <tr>
    <td>Workshop and dinner</td>
    <td> <label>
      <input type="radio" name="redirectOption" onclick="setRedirectUrl('https://uusalesservices.uu.nl/international-conference-software-business-workshop-and-dinner')" /> € 350.00 </label> </td>
      
     <td></td>
  </tr>

      <tr>
    <td>Dinner</td>
    <td> <label>
      <input type="radio" name="redirectOption" onclick="setRedirectUrl('https://uusalesservices.uu.nl/international-conference-software-business-extra-page-springer-proceedings')" /> € 100.00 </label> </td>
      
     <td></td>
  </tr>
  </table>

</p>

<p><b>Please note: Each full or short paper must have a unique registered presenter. This policy applies also to PhD Retreat.</b></p>

<p><button class="styled-button" onclick="redirectToSelected()">Register</button></p>



<p><b>Purchase Extra Pages for Your Accepted Research Paper</b></p>

We also offer the possibility of buying extra pages for your accepted research paper.

<ul>
    <li>100 € for one extra page: <a href="https://uusalesservices.uu.nl/international-conference-software-business-extra-page-springer-proceedings" target="_blank">Purchase here</li>
    <li>200 € for two extra pages: <a href="https://uusalesservices.uu.nl/international-conference-software-business-two-extra-pages-springer-proceedings" target="_blank">Purchase here</li>
    
</ul>


<p><b>Cancellation policy</b></p>
<p>Cancellation Fee</p>
<p>
  <ul>
    <li>All cancellations will incur a fee of 150 euros, regardless of the timing of the cancellation.</li>
  </ul>
</p>

<p>Cancellation Deadline</p>
<p>
<ul>
    <li>Cancellations made more than one month prior to the conference start date will be eligible for a refund minus the 150 euro cancellation fee.</li>
    <li>Cancellations made less than one month before the conference start date will not be eligible for any refund.</li>
    
</ul>
</p>
<p><b>Privacy Policy</b></p>

By registering to this event you accept that the personal information you provide will be used by the hosting organization(s) in connection with the administration of the event, and may be shared with the service providers when necessary.
