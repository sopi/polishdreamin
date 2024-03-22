# Step 3 - Build a Solution
<details>
  <summary>Custom Field for First Contact Time</summary>
Guide me through salesforce admin steps to create to create a custom date-time field on the Lead object to record the exact time when a lead is first contacted. This could be named something like "First Contact Time."

https://chat.openai.com/share/84d29e32-9b1f-45ef-b2e7-ec696ec367e3
</details>

<details>
  <summary>Automation for Tracking First Contact</summary>

Use Salesforce's Process Builder or Flow to automate the process of capturing the first contact time. The automation should be triggered when a lead is contacted for the first time. Depending on how your organization defines "contact" (e.g., a call, email, or meeting logged in Salesforce), you can set the appropriate criteria for the automation. When the criteria are met, the automation updates the "First Contact Time" field with the current timestamp.
* Flow - Lead
https://chat.openai.com/share/5f1a187d-4619-4489-8acb-baaddb1babb9
* Flow - Task
https://chat.openai.com/share/b00ee4fc-34c5-4455-be0f-251ba449240f
* WhatId vs WhoId: https://chat.openai.com/share/1c10be71-9301-46d7-8225-5f9057e203ee
 </details>
</details>
<details>
  <summary>Calculated Field for Waiting Time</summary> 
https://chat.openai.com/share/5934f333-4cfa-47f9-b345-8abd47d11df5

Additional prompt for formula images: https://chat.openai.com/share/5f951362-bb2b-4c58-b62f-4ef81e687432
  </details>  
<details>
  <summary>Lead List View Customization</summary>
https://chat.openai.com/share/5f951362-bb2b-4c58-b62f-4ef81e687432
</details>    
<details>
  <summary>Historical Reporting</summary>
https://chat.openai.com/share/9066a7f4-5e4b-4113-8ea2-d3568e5a1086
</details>  
<details>
  <summary>LWC</summary>
https://chat.openai.com/share/4a2b098f-5d95-457f-8d5d-764ff21b2c2e
```
Please guide me through the Salesforce developer steps to create a live digital clock showing the elapsed time from lead creation until the first contact on the lead detail page. The first contact time (First_Contact_Time__c) field exists on a lead. It can be empty or filled. This component would dynamically display the time elapsed since the lead's creation, updating in real-time as you view the page as a digital clock that will work as a clock showing the live elapsed time when browsing a lead page. It would freeze once the first contact has been made, showing the final elapsed time. Additionally, the background should be changed based on elapsed time: below 24h green, below 48h orange, and the rest red.
Examples of displayed elapsed time:
1: 05h 03m 21s
2: 1d 06h 03m 21s
3: 1s 
4: 2m 34s
5: 4h 2m 34s
```
</details>

### Flows:
Clear instructions Set vs. update :) When talking to person that understands Flows can use this interchangeably: we know to set connection, but AI doesn’t know, and when we write update i tries to solve it and make an update.