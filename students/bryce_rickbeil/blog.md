# Research Blog

Add a new entry each week (or more often if you like). Be honest — write what actually happened, not just what went well. This log will help you write your final report.

---

## YYYY-MM-DD

**What I worked on:**
_Describe the main tasks, experiments, or analyses you did this week._

**What helped:**
_A paper, a conversation with your mentor, a tutorial, a tool — what moved you forward?_

**What was challenging:**
_A bug, a confusing result, something you couldn't figure out — write it down even if unresolved._

**What I learned:**
_One or two things you understand better now than you did last week._

### Log
## 2026/05/29
This week I was able to read through papers and documents pertaining to RadClss, Py-ART, MC3E, github, etc.
I was also able to somewhat navigate the github repository and commit a test text file to my fork of the 
repository. Earlier in the week I attended both orientation sessions and had a meeting with Joseph about 
the scope of the project and what are some of the next steps going forward. 

The paper describing how to navigate and use github was really helpful in understanding the basics of how to
use github. 

Getting github set up on my computer and trying to commit files to github was challenging. I also had issues
with the subsystem that was setup on the office computer which may need to be resolved sooner rather than later.

I now do have a better understanding of operating and using github and I also learned more about the MC3E feild
campaign and RadClss software which will both be very important going forward.

Plan for this next week is to set up coding environment, plot radar data with aircraft overlays from the May 
20th event, make GIFS for that associated event, and if time allows work on incorporating those GIF images 
into the GUI that was being developed by Christian.

## 2026/06/05
This week I worked mainly on getting more familiar with the Py-ART code and a lot of different cool methods for 
plotting radar data. Half way through the week I was able to get a hold of radar data from C-SAPR during the time
of the MC3E field campaign around the May 20, 2011 day. I was also able to locate flight data for this day which 
led me to making a bunch of gifs that showed not only just the C-SAPR radar data but also overlayed flight tracks
during this day too. This has allowed me to have multiple code files that all have little bits and pieces that will
be useful for making the final Rad-CAT product.

Having a couple of conversations with Joe helped me locate alot of different data that was important for going 
forward in the writting of code. 

Locating the data was very challenging as none of the data was in one nice place and thus resulted in a lot of time
spent trying to not only find the data but also being able to download it was a challenge in itself...

I have learned better how to use the Py-ART library and also am more able and comfortable in navigating the github 
repository. 

## 2026/06/12
This week I worked on code that would find which elevation sweep the Citation aircraft was in and then would plot a ppi 
of just that sweep along with code that would generate a sudo RHI scan of the vertical cross section that the aircraft 
was in. Then I was able to find the data file containing all of the cloud microphysics observations from the citation
and display some of the parameters and compare them with some of the reflectivity values that I earlier found. I also 
worked on code that would create a time series plot of radar reflectivity above, on, and below the aircraft based on
its location and then add that extra data into the data array containing the other microphysics data. Then as of more 
recent I have been working on and will still be finishing up figure creation of sudo RHI scans to then compare some of 
these with the data that I am extracting. I also started on a draft of the introduction to the final SULI paper too.

Something that was and still is confusing is matplotlib not fully plotting my 10 second interval data, my guess is it has
something to do with how matplotlib is defining intervals and how my intervals are but I am not for sure. 

I have definetly become more comfortable with retrieving data from the ARM data base as I was more easily able to get the
citation observation data this time around. 

Next week I will try to finish up the sudo RHI images for comparison and I would also like to talk with Joe further 
about my methodology of data extraction to make sure that the method makes sense. 
---
