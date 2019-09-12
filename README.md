# Hand Hygiene Observation Toolkit Handbook
The Explanatory Handbook for the Hand Hygiene Observation Tool.

# Background

The Hand Hygiene Observation Toolkit (HHOT) was designed by MSF to enable users in the field health facilities to observe, record, analyse and share hand hygiene observations. The toolkit covers data collection (using a phone or tablet) and analysis using a dashboard. The dashboard allows analysis of hand hygiene adherence across facilities, wards and staff groups. This information can inform decision-making and interventions at sites where hand hygiene can be improved.

Note: The MSF version of the HHOT uses PowerBI to do the analysis via an interactive dashboard. As we think this toolkit may be useful to other organisations and institutions, we have developed an excel version of the dashboard (as PowerBI is not commonplace). This excel deshboard is untested in field conditions and has been developed as a starting point for organisations looking to develop hand hygiene auditing to improve quality of care. MSF does not offer support on the implementation of the tollkit described below and recommends full testing before deployment.

A study on the use of HHOT as an effective tool in improving hand hygiene adherance in an MSF facility [can be found here in the Jama Open Network journal](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2747754).

**If you are reading this and you work in an MSF Facility, please contact your IPC lead to find out how to use the MSF version of the toolkit**

The HHOT is based on the WHO [5 Moments for Hand Hygiene approach](http://www.who.int/gpsc/5may/Hand_Hygiene_Why_How_and_When_Brochure.pdf).  

The HHOT measures adherence to the following 5 hand hygine moments: 
* % before touching patient
* % before clean procedure 
* % after bodily fluid risk 
* % after touching patient 
* % after touching patient surroundings


The starter kit for **5 Moments** [can be found here](https://www.who.int/gpsc/5may/tools/en/).

This HHOT handbook explains how to collect data on the 5 moments of hand hygiene, and how to visualise it within the HHOT dashboard. 

The handbook takes you through seven stages:
1. How to create a KoBo Toolbox account (for data collection and storage)
2. How to create Your Data Collection Form 
3. How to deploy Your Data Collection Form 
4. How to collect your data
5. How to download your data
6. How to input your data into the HHOT dashboard
7. How to analyse your data in the HHOT dashboard 

By the end of this process, you should have a working HHOT dashboard.
[Here is a downloadable example of the dashboard using dummy data.](Example%20Folder/HHOT%20Dashboard%20Example%20.xlsb).

And, here is a screenshot of what the dashboard looks like when it is in use. 

![](Screenshots%20folder/1%20HHOT%20dashboard%20in%20use%20(1).png)

# Stage 1: How to create a KoBo Toolbox account

**Objectives of step** 
* Create KoBo Toolbox account in order to collect hand hygiene observation data.

**Estimated time for task**
* Two minutes.

1. [Click this link to go to Kobo Toolbox](https://www.kobotoolbox.org/). 
2. Select sign-up, and choose either a Humanitarian Organizations or Researchers account - what follows will work with either.
3. Follow the on-screen instructions, including confirming the account by clicking the link sent to your email address. 

You have now created the platform for data collection and storage. The next phase will be formatting an observation survey for data collection. 

Please note: We have found Kobo works best in Google Chrome. 

# Stage 2: How to create Your Data Collection Form 

**Objectives of step**
* Correctly format your data collection form in preparation for uploading to Kobo. 

**Estimated time for task**
* This task requires configuring the data collection form template provided, how much time it takes depends on the amount of edits made (so how many sites/facilities you wish to collect data on).

The data collection form template is a generic version that can be adapted to your needs. It is currently formatted with generic names (eg: Department 1, Facility A), so you will need to edit these to reflect the facilities you wish to monitor. 

1. [Download the data collection form template by clicking here](Data%20Collection%20Form%20%20.xlsx). (Please note, when downloading a file from Github, you have the options to either 'view raw' or 'download' - either works in this situation.)
2. Only edit the contents in the choices tab (the purple tab named **choices**). Please do not edit the other tabs. When editing the choices tab, please note: only cells in column C should be edited. You must keep the format of the rest of the file when editing, otherwise the data you generate with Kobo will not be transferable into HHOT dashboard.
3. Add your 'department' names (row 4-8 of column C). A department describes a group of facilities. If you have less than 4 departments, please delete the rows that are not needed. If you have more than four, please insert new rows below row 8.
4. Add your facility names (column C, row 9-34). Note that each facility relates to a specific department. In the example, department Montreal contains seven facilities on rows 7-13 and the form is colour coded to reflect this. Again, please delete any facility rows not used and insert new rows if you have more facilities than space. 
5. Save the form. Make sure to give it a distinct name. 
6. You are now ready to upload the form to Kobo Toolbox. 


# Stage 3: How to deploy Your Data Collection Form 

1. Open [KoBo Toolbox](https://www.kobotoolbox.org/), and log into your account. 
2. Next select **new**, then **upload an XLSform**. Upload your data collection form. 

![](Screenshots%20folder/2%20Upload%20XLSForm.png) 

3. Once your data collection form is uploaded, **deploy** the form to make it active, and ready for data collection. 

![](Screenshots%20folder/3%20deploy%20form.png)

4. The default KoboToolbox setting is that only the signed in user has access to the uploaded form and the data. There is the option to grant access rights to other KoboToolbox users. For more information please [click here](http://support.kobotoolbox.org/en/articles/592376-managing-permissions).

# Stage 4: How to collect your data

1. Your data collectors will now be able to access and complete the data collection form. They can do so via the KoboToolbox data collection app, which is called ['KoBoCollect'](https://play.google.com/store/apps/details?id=org.koboc.collect.android&hl=en_GB) or via [hyperlink](http://support.kobotoolbox.org/en/articles/592441-collecting-data-through-web-forms). **This app in only available on Android devices.**
Note: The Kobo Collect app works better if you are observing hand hygiene in an environment without connectivity, but make sure you set it up with an internet connection of some kind to begin with.
2. Your data collectors should use a new form for each observation 'session' (which can include multiple observations). Please ensure your data collectors put their own name in the name box and not the person they are observing. 

![](Screenshots%20folder/4%20example%20of%20form%20in%20use.png)

3. Once data has been collected using the form, Kobo Toolbox will generate a **data** page for it. These will appear as individual forms with the names of the collectors.  

More information on form accessibility and use can be found [here](http://support.kobotoolbox.org/collecting-data/recommended-devices-for-data-collection). 


# Stage 5: How to download your data

**Objectives of step**
* To export your data from Kobo Toolbox into Excel in order to then input your data into the HHOT dashbaord.

**Estimated time for task**
* Two minutes, depending on dataset size and internet connectivity.

**Example:**
[Kobo Data Download Example](Example%20Folder/Kobotoolbox%20Data%20Download%20Example.xlsx)

1. In your Kobo Toolbox account click on the name of the project, which takes you into the summary page. 

2. Select **Data** at the top of the page. 

![](Screenshots%20folder/5%20data%20section%20shown.png)

3. From the list on the left-hand side, select **Downloads**. 
4. In the **Download Data** criteria, make sure the **Export type** is **XLS** and Value and header format is **XML values and headers**. 

![](Screenshots%20folder/7%20downloading%20from%20kobo.png)

5. You are now ready to download your data. Click **Export** and then the download button. Depending on the size of your data and strength of wifi this may take a little time. 

# Stage 6: How to input your data into the HHOT dashboard

**Objectives of stage**
* To add your observation data to the HHOT dashboard and to configure the dashboard. 

**Estimated time for task**
* 30+ minutes, depending on the size and type of your dataset. You may need to configure the HHOT dashboard which will take longer. A estimate is difficult in this context, but this is likely to be one  of the more lengthy steps in the process.

**Example:**
[Here is a downloadable example of the dashboard using dummy data](Example%20Folder/HHOT%20Dashboard%20Example%20.xlsb). 

1. First open the [HHOT dashboard template](HHOT%20Dashboard%20.xlsb).

If you are unable to see all tabs, please hit the '...' button at the bottom of the page and this will expand the tabs.

**LIGHT GREEN TABS**: Your downloaded data goes in these tabs. These tabs are called **HandHygiene Observation tool** and **OBSERVATION_REPEAT** - you will notice these have the same names as the tabs on your downloaded data. 

**BLUE TAB**: The blue tab lablled **lists**.This tab will need to be configured to reflect you department and facility names (as in the data collection form). How to do this is explained below.

**RED TABS**: These tabs lablled **data_manipulated**, and **tables** are for calculation purposes and should not be edited. Please, **DO NOT EDIT THESE PAGES**. 

**DARK GREEN TAB**: This tab, labelled **ANALYTICS** is where the interactive dashboard will be displayed. How to use this is explained in Stage 7.

2. **Copy and paste** the data from both tabs in your downloaded data spreadsheet into the light green tabs **Hand Hygiene Observation Tool** and **OBSERVATION_REPEAT**. 

* Data from the first tab (**Hand Hygiene Observation Tool**) must be pasted into the tab also called **Hand Hygiene Observation Tool** in the HHOT dashboard.
* Data from the second tab (**OBSERVATION_REPEAT**) must be pasted into the tab also called **OBSERVATION_REPEAT** in the HHOT dashboard.
       
3. Go to the HHOT dashboard **lists** tab (the blue tab).  
4. Edit the department names to match the configuration you used for the data collection form. The HHOT dashboard template has generic names prepopulated that must be replaced. 

* Department names go under Column A **and** on Row 1.  Please remember to update both row AND column so they reflect the departments you used in the data collection form.
* Facility names go under each respective Department column (in our example: Montreal Facilities are under Column B, London Facilities are under Column C, etc.) 

* Please delete any unwanted Department/Facility and add any extra Department/Facility. 

5. Ensure that **“ALL”** is present at the end of every column as a Facility choice. This will ensure that you can visualise an overview of all your facilities if you wish. The formatting must be exactly like that in the provided example, and in the below screenshot. This includes the blank spaces. If you had more categories in your data collection form configuration, then add those in but please remember to have your final collumn 'E' in this example, say **'ALL'** in both the first and second row.
![](Screenshots%20folder/8%20ensuring%20'all'%20is%20there%20.png)
6. To adjust the defined names, press **CTRL+F3** to open the Name Manager (or on Macs: ⌘ + fn + F3). By default, the generic departments are used for **Defined Names**.
7. Click on **“Edit”** to modify each applicable category.

* The **Name** column (DEPA, DEPB, DEPC, DEPD, DEPE) must be modified to reflect the same deparment names as on the **lists** tab (Montreal, London, Nairobi).

Please ensure complete accuracy at this stage as any error could cause issues at later steps. This is likely one of the most difficult steps in this process, so please be careful. 

# Stage 7: How to analyse your data in the HHOT dashboard

**Objectives of stage**
* To visualise and analyse your data in the HHOT dashboard. 

**Estimated time for task**
* Not applicable

Please ensure that the Calculation Options are set to **Automatic**. Go to the Excel Ribbon to do this.

![](Screenshots%20folder/9%20setting%20to%20automatic.png)

1. First input the dates for the time period you would like to visualise / analyse. Use this format: **day/month/year.** 
2. Enter whichever department, facility, ward or profession filters you would like to visualise / analyse into the criteria table columns, using the dropdown menus.  Then press refresh and the data analysis should be carried out for you. Adjust the criteria in the table, depending on what data you want to analyse, for example doctors handwashing hygiene in the burns ward of UCLH. 

If you are having issues at this step it is likely due to a issue with dashboard configuration. Try retracing your steps through Stage 6 of the process, looking for configuration errors. 

Here is a example of what a correct download looks like. 
[Kobo Data Download Example](Example%20Folder/Kobotoolbox%20Data%20Download%20Example.xlsx)

Here is a example of what the HHOT fomatting looks like in use, it may be useful as a point of reference.
[Example HHOT tool](Example%20Folder/HHOT%20Dashboard%20Example%20.xlsb)

It could also be a issue with the changes made to the 'lists' page, please double check that the changes made match those made earlier to the data collection form. 


Either... **Congradulations! You now have visualised your data!** or you are having issues visualising your data. If the latter, please try the following steps. 

1. Refresh the page and go to the pivot table on the left hand side of the page. Turn the option to **“true”** for date range. 
2. Then, ensure the pivot table is accurate. The **Row Lables** should match the **Departments** that you have selected in the **Desired Criteria** section. Double click the drop down under **Row Lables** to generate the options availible. 

If this is proving difficult, refresh the page again. 

Here is a step by step guide on [how to referesh a pivot table](https://support.office.com/en-us/article/refresh-pivottable-data-6d24cece-a038-468a-8176-8b6568ca9be2)

If you are having issues with this step it may be that the chagnes made to the 'lists' page are still inconsistant with your data download from Kobo Toolbox, please double check this. 

If you there are any errors in this guide, or you want to improve on the current toolkit or the guide, please document as issues on this github project.
