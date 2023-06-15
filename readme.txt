Imagine you're a front end UI developer. We need to build a tool to be used by a customer service rep to generate beautiful looking custom data and revenue reports with insights for our customers. 
The customers are all travel affiliate partners, and the raw data contains information of the hotel bookings and other travel product sales associated with their account. 
The raw data is available in two separate CSV files. One file is generated from airplane.dev task, and the other is downloaded from hub.stay22.com. 
Both these CSV files contain the same data but have different head rows. 
The tool should be able to either accept both these CSV as separate uploads or obtain the data automatically with webhooks or API or Zapier integrations, depending on viability. 
The interface should allow the user to either upload the two different CSV files and get a validation that the input files / obtained data is in the expected format. 
The interface screen should have different buttons corresponding to different report generators. Examples of reports are - comission aging projections, cancellation trends, most booked hotels,
best performing providers, monthly booking performance reports, source of bookings direct vs pop and so on. I can think of at least 7 possible reports that can be generated. 
The tool's interface should have a common viewport where the results of each report generator is displayed as and when the button is clicked. 
Finally, there should also be a way for the user to choose the available reports, generate them and compile the results into a pdf which can be emailed to the partner. 

I will define the contents of the head row of both CSV files. I have access to a heroku server for hosting a web app if that is the best way to build this tool. I have very limited developer knowledge, so I would prefer a solution
which is not too complicated. I can follow step by step instructions to build this tool. 

I will also describe the logic and data manipulation and rules required to process data on both these sheets in future prompts. 

As a modern, professional front end UI designer, how would you go about building this tool? 

--------------

Provider report: 

