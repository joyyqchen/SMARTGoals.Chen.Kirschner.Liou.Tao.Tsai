Earthquake Project: Team 9
=============================
###Collaborators
<table border="0">
<tr>
<th>Name</th>
<th>Role</th>
<th>GitHub Id</th>
</tr>
<tr>
<td>Joy Chen</td>
<td>Visualizer</td>
<td>@joyyqchen</td>
</tr>
<tr>
<td>Lorraine Hsiao</td>
<td>Visualizer</td>
<td>@lorrainehsiao</td>
</tr>
<tr>
<td>Sam Kirschner</td>
<td>Visualizer</td>
<td>@drmeow</td>
</tr>
<tr>
<td>Brian Liou</td>
<td>Presenter</td>
<td>@brianliou</td>
</tr>
<tr>
<td>Eric Tsai</td>
<td>Visualizer</td>
<td>@wxadqcze</td>
</tr>

</table>



###Task at Hand: Task 2
-------------------------------------------------------------------
<i>From the task list in the Issue Tracker of the Presenters Repository</i>
<br><br>
<b>Researching and Negotiating on Data Formats:</b>
- Curator: Construct interface for Curators and Visualizers to to utilize
- what is the most common one
- JSON versus CSV versus XML
- Data Frame versus 2-D Array versus List of Dictionaries
- Analyzers/Visualizers: research sufficient/functional data formats in terms of ease-of-use and ability to produce visuals
- Presenters: decide on how to present the data
- iPython notebook, HTML, etc.
- what are the pro’s and con’s of each method
- which format could be used to make the graph dynamic?




###SMART Goals
-------------------------------------------------------------------
1. Determine which data format would be most appropriate for data curators to export/analyzers to use as inputs
2. Understand what data parameters come out of an ETAS/MDA Model
3. Create a standardized data format/structure for the outputs from the ETA/MDA Model
4. Test to see if the formatted data can be imported into a visualization tool to be visualized* <br>
<i>*Since the actual data is currently unavailable, create proxy "fake" data in the same structure and format that we expect the real data to be in and test (4) using that data</i>
5. Learn and understand the basics of D3
6. Think about which tools/packages within R can create the best visualizations given the data we are working with

###SMART Goal Results
-------------------------------------------------------------------
1. Our group has determined that the CSV format would be most appropriate for data curators to export for analyzers to use in the models. CSV has the most efficient and simple structure and can be easily imported/disected by the analyzers. We have also determined that it would be helpful for the data curators to also publish the same data in JSON format for the visualizers. If some visualizers want to create graphs in D3, the JSON format would be most adaptable.<br><br>
2. Roland has sent us a link to the iPython notebook his group is working on and we can run it to see what parameters are outputted
3. Based on the iPython notebook we looked at, this is a potential sample data format that Roland's group should export to us in CSV form:
 <table border="0">
<tr>
<th></th>
<th>City</th>
<th>State</th>
<th>Latitude</th>
<th>Longitude</th>
<th>Magnitude</th>
<th>Duration (minutes)</th>
<th>ETAS Probability</th>
<th>Stark Probability</th>
<th>Alarm Process Range</th>
<th>SAPP</th>
<th>PT Process</th>
</tr>
<tr>
<td><i><b>Sample</i></b></td>
<td>San Diego</td>
<td>California</td>
<td>57.053056</td>
<td>-135.33</td>
<td>3.0</td>
<td>1.5</td>
<td>0.25</td>
<td>0.33</td>
<td>Talk to Roland's Group</td>
<td>Talk to Laura's Group</td>
<td>Talk to Laura's Group</td>
</tr>
</table>

4. <b>MDA Alarm Windows.jpg</b><br> A visualization depicting the magnitudes of earthquakes in Southern California over time with blue and red lines overlaid that symbolize the start and stop times of the alarm, respectively.Please refer to <i>MDA Alarm Windows Plotting Notebook</i> for the code used.<br>
<img src="https://github.com/joyyqchen/EarthquakeProject.Team-Chen.Hsiao.Kirschner.Liou.Tsai/blob/master/MDA%20Alarm%20Windows.jpg?raw=true" alt="MDA Alarm Windows" width="850" height="600">


