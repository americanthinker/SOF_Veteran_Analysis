# The Story of the Special Operations Veteran community: In Transition  
  
  
<p align="center">
  <img align="center" src="/images/NavySEALs.png" width="600" title="Navy SEALs">
</p>  
  
  
# Setting the Stage: Background Part I
The US Special Operations community is a diverse group of highly trained men and women dedicated to the cause of ["protecting and advancing U.S. policies and objectives across the international arena"](https://www.socom.mil/about).   The community is composed of Special Operations Forces (SOF) "tribes" from all branches of the Department of Defense to include the Navy SEALs, Army Green Berets, Air Force Pararesucmen, and Marine Raiders, among other specialized units.  This highly talented subset of the overall US population, at some point in their military career, makes the decision to "put down their ruck sack", "hang up their uniform" and transition into civlian life. 

<p align="center">
  <img align="center" src="/images/mil-civ.png" width="200" height="250" title="Mil to Civ">
</p>

As a former SEAL turned Data Scientist I partnered with [Elite Meet](https://elitemeetus.org/) - a 501(c)(3) non-profit Veteratn Service Organization dedicated to providing a post-military SOF network and connecting its members to leaders in the Corporate sector - to conduct an analysis on this group of veterans to paint a holistic picture of who they are and where they are headed.  This analysis answers the following questions:
- Where does this post-military network live?
- What is the composition (by tribe) of the overall community?
- What are the descriptive charateristics of this group: Age, Education, XXX
- How prepared is this group for the Corporate workforce?
- What is the growth over time

# The Data
I was granted access to an anonymized section of the Elite Meet (EM) membership database which consisted of 750+ entries of SOF veteran members.  This initial dataset was curated from the EM Salesforce instance, which in turn was collected from individual membership intake forms at time of EM application.  Because many of the intake form fields were free form, the dataset required an extensive amount of cleaning in order to conduct an accurate analysis.  As an example, something as simple as inputting a "Current Location" oftentimes included several variations, as shown in the figure below: 
<p align="center">
  <img align="center" src="/images/Excel_cleaned.png" width="500" title="Data cleaning">
</p>
The dataset originally contained more than 50 features/columns, but after reviewing the data I was able to reduce the number of features to 34.  Here's a quick look at what the set looks like:
<p align="center">
  <img align="center" src="/images/Data-shot.png" width="500" title="Data cleaning">
</p>

## Community Breakdown by Tribe
<p align="center">
  <img align="center" src="/images/SOF-Breakdown.png" width="500" title="SOF Tribes">
</p>
