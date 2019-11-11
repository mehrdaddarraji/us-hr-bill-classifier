Dataset Selection: Congressional Bill Status
1. Describe the dataset. (ex: The number of microaneurysms found in a patient's eye and whether or not they have diabetic retinopathy; or Lending Tree loan data, including who defaulted and who paid off their loan.)
The past and current congressional bill status with the US House of Representatives starting from the 113th Congress to the current present day session. This includes weather or no has the bill been processed, referred to committee, read on the floor, had been amended, or voted/roll-called on.
2. How many records does the dataset have? 
Based off of past congressional session which include the 113th, 114th and 115th session, we have a total of 20,206 records or number of bills introduced. We can only go until the 113th congress, as that's where digitization of congressional info starts and is available. For the 116th, or the current congress, we have a total of 6,309 to this date. 
3. How many features does the dataset have? List or describe a few of them.
For each bill, depending on the popularity, and overall actions of the bills we have approximately 30 features that range from quantitative measures to more quality version of text. Some include who the names of the cosponsors and sponsors, legislative topics, policy area, bill number, title, date introduced, amendment, related bills, committee referred to, and recorded votes. Some of the more qualitative measures include bill referrals, considerations by house, and general debates to name a few.
4. What can you try to predict in this dataset? (ex: We can use the number of microaneurysms measured in the patient's eye to predict whether or not they have diabetic retinopathy; or We can try using the features, including age, income, home ownership status, etc, to predict whether or not someone will default on their loan.)
Due to the multiple steps a bill can take, it can result to be stopped or not even make it to the house floor. Utilizing the features mentioned above we want to predict weather a proposed bill will be voted upon and pass the US House of Representatives. 
5. Is this a labeled dataset, appropriate for a supervised learning classification problem? (In other words, if you are trying to predict whether or not someone has a disease, does your dataset contain whether or not each record has the disease?)
The dataset is labeled, with specific codes for each action a bill can take, established by Government Publishing Office (GPO). 
6. Provide a link to the dataset, if there is one. If you are getting your data from somewhere other than a link, where are you getting it from?
Example Link for the 115th Congress: https://www.govinfo.gov/bulkdata/BILLSTATUS/115/hr
*Includes a .zip file that includes all the XML files. 
Here is also a resource on how the XML file is formatted and labeled codes of actions: 
https://www.govinfo.gov/bulkdata/BILLSTATUS/resources/BILLSTATUS-XML_User-Guide-v1.pdf 


