# apply.fyi for KL

https://apply.fyi/ is a crowdsourced and averaged online and UT Austin salary data and internship application links that lets people see compensation and easily apply to 180+ SWE internships really fast. It's created by Rithwik Pattikonda and I stumbled upon it on [Hackathon Hackers](https://www.facebook.com/groups/hackathonhackers/permalink/2803977606324373/) facebook group

I'm making a little clone of that for Kuala Lumpur tech internships.


## what needs to be done next:
* Manually gather 10+ initial salary data from the community 
* add UI search (filter) functionality 
* Enable "Add Your Salary" functionality 
    * a Google form (and its Google Sheets) are already connected to the app (Vue renders data from a G Sheet associated with a G Form)
    * since there can be multiple salaries for one company, an _averaging_ function could be used to show the average company salary maybe
* Enable "Report Data" functionality in case the table pisses any company off
* Add "Apply for internship at this company" link to each row?
* *What else? Pull Requests are welcome*
* get a domain maybe

## stack
* Google Sheets as backend (reading results as JSON)
* Vue.js for rendering data


