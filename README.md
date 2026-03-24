I want to build one Ai python streamlit project as follows,

Domain: Speech
Title: wildlife sound intelligence
Ai-model / API: Groq api

Python modules: streamlit, groq

Working of the project,
Record wildlife sounds -> identifies species -> classification+behavior analysis+ecosystem insights
 """
Analyze the given wildlife sound.

Return output ONLY in this format:
Species: <name>
Behavior: <behavior>
Alert: <None/Distress/Predator/Human>
Confidence: <0-100>

Do not write any explanation.
"""
Reports and outcomes,
1. Audio Detection Flow with Next Button
Record wildlife sounds continuously
System identifies species from each audio input
On clicking Next Button, the system processes and plays/analyzes the next recorded sound segment
Displays species name + behavior insight for each step

Data Labels for Visualization:

Audio Segment ID
Species Identified
Confidence Score (%)
Timestamp
2. Dashboard – Wildlife Activity Monitoring
Total recordings captured
Active species count
Time of peak activity
Location-based sound mapping (if GPS enabled)

Data Labels for Visualization:

Number of Recordings
Species Count
Activity Time (mins/hr)
Location Coordinates
3. Obstacle / Alert Tabs (Anomaly Detection)
Detect unusual or critical sounds (distress calls, predator presence, human interference)
Classify alerts into categories
Store audio clips for each alert

Data Labels for Visualization:

Alert Type (Distress / Predator / Human Activity)
Severity Level (Low / Medium / High)
Detection Time
Audio Clip Reference
4. Final Journey Report (Start → End Analysis)
Complete summary of all recorded audio sessions
Species identified throughout the process
Alerts/obstacles detected
Timeline of events with audio references
Dashboard analytics in visual format

Data Labels for Visualization:

Total Duration
Total Audio Samples
Species Detected List
Number of Alerts
Event Timeline
5. Visualization & Data Labeling (Overall Insights)
Graphs showing species distribution and behavior patterns
Timeline of wildlife activity
Alert frequency chart
Ecosystem insight summary

Data Labels for Visualization:

Species Name
Detection Frequency
Behavior Type
Time Interval
Alert Count
Constraints,
1. My entire project should be in a single file with usaging any secrts, .env such file
2. My code should be very optimised to 100 lines only
3. I need to take audio file input of user to set desination as a command
add mic button to take live audio  record of user command to navigate.
Build the LLM such that the audio file data should be processed as diffrent outcomes
 The UI of the project can be a single webpage with tabs. 
The webpage shuld be neatly alight and better UI
The visualizations should be a pie, bar, line charts and other KPI gauges ... using matplotlib, pandas, plotly
Train the LLM or APi such that it should more flexible and accurate and also it should be robost in operation.


The output code must shold be below 100 lines
The only APIs are used for our API, and our api must be  only in main app.py file, not any other secrets or dotend
The file report may consist of 
   -i) input data voice 
  -ii) Proceed with result sumary (transcribe audio)
  -iv) visualisations,
   -v) conclusions
updates on this version
1. Input files can also be mp3, ogg, wav and other
3. The downloaded file should be a PDF with proper layouts and margins and follow as a document.
