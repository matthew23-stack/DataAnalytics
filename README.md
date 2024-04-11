# DataAnalytics

# Module 1: The Basics of Data
What is Data Analytics?🙌🙌
The role of a data analyst is to transform raw data into actionable insights that guide decision-making processes within an organization.involves several key responsibilities and skills.Data Collection and Preparation:Sourcing data from various channels, including databases, spreadsheets, and external sources,Data Analysis:Employing statistical methods, machine learning techniques, or other analytic tools to interpret data,Data Visualization and Storytelling:Creating visual representations of the data, such as charts, graphs, and dashboards, to make complex information easily understandable,Decision Support:Making recommendations based on data-driven insights to help guide business decisions,Continuous Learning and Adaptation:Keeping up-to-date with the latest industry trends, tools, and technologies in data analysis.A data analyst helps an organization make informed decisions that can improve operational efficiencies, drive business strategies, and create a competitive advantage.Professionals who possess the skills and knowledge required to perform this vital work.They understand how the organization can acquire, clean, and transform data to meet the organization's needs.
Data ✨✨
The amount of data the modern world generates on a daily basis is staggering. From the organized tables of spreadsheets to the storage of photos, video, and audio recordings, modern businesses create an almost overwhelming avalanche of data that is ripe for use in analytics programs.
Storage🎂🎂
The second key trend driving the growth of analytics programs is the increased availability of storage at rapidly decreasing costs.
Computing Power✔✔
Today, the effects of Moore's Law have democratized computing. Most employees in an organization now have enough computing power sitting on their desks to perform a wide variety of analytic tasks. If they require more powerful computing resources, cloud services allow them to rent massive banks of computers at very low cost. Even better, those resources are charged at hourly rates, and analysts pay only for the computing time that they actually use.
Career in Analytics🎁🎁
As businesses try to keep up with these trends, hiring managers find themselves struggling to identify, recruit, and retain talented analytics professionals.Data analysts and scientists,AI and machine learning (ML) specialists,Big Data specialists,Digital marketing and strategy specialists,Process automation specialists,Business development professionals,Digital transformation specialists,Information security analyst,Software and applications developers,Internet of Things (IoT) specialists.
The Analytics Process👌👌
Analysts working with data move through a series of different steps as they seek to gain business value from their organization's data.
![image](https://github.com/matthew23-stack/DataAnalytics/assets/127289268/a84e8897-36d0-4f34-9159-7e6dc4baccb7)
The Analytics Process is Iterative
While we describe the steps of the analytics process as a series of sequential actions, it is more accurate to think of them as a set of interrelated actions that may be revisited frequently while working with a dataset.
Analytics Techniques🐱‍🏍🐱‍🏍
Analysts use a variety of techniques to draw conclusions from the data at their disposal.help you understand the purpose of different types of analysis, we often group these techniques into categories based on the purpose of the analysis and/or the nature of the tool.
Machine Learning, Artificial Intelligence, and Deep Learning🐱‍🚀🐱‍🚀
Machine learning uses algorithms to discover knowledge in your datasets that you can then apply to help you make informed decisions about the future. here are some cases where machine learning commonly adds value:Segmenting customers and determining the marketing messages that will appeal to different customer groups.Discovering anomalies in system and application logs that may be indicative of a cybersecurity incident.Forecasting product sales based on market and environmental conditions.Machine learning can bring value to almost every field where discovering previously unknown knowledge is useful.As we move through the world, we hear the terms artificial intelligence, machine learning, and deep learning being used almost interchangeably to describe any sort of technique where computers are working with data.Artificial intelligence (AI) includes any type of technique where you are attempting to get a computer system to imitate human behavior. As the name implies, you are trying to ask computer systems to artificially behave as if they were intelligent.Machine learning (ML) is a subset of AI techniques. ML techniques attempt to apply statistics to data problems in an effort to discover new knowledge. Or, in other terms, ML techniques are AI techniques designed to learn.Deep learning is a further subdivision of machine learning that uses quite complex techniques, known as neural networks, to discover knowledge in a particular way. It is a highly specialized subfield of machine learning that is most commonly used for image, video, and sound analysis.
Data Governance🐱‍🐉🐱‍🐉
Notice that there is a slab of stone that supports the three pillars of analytics. This slab represents the important role of data governance in analytics programs. Without strong governance, analytics programs cannot function effectively.Data governance programs ensure that the organization has high-quality data and is able to effectively control that data.how organizations use master data management (MDM) programs to maintain and improve the quality of their data.
Analytics Tools🐱‍💻🐱‍💻
hese tools automate much of the heavy lifting of data analysis, improving the analyst's ability to acquire, clean, manipulate, visualize, and analyze data.Some of these tools are well-known to most computer users. For example, people are generally familiar with spreadsheet tools such as Microsoft Excel or Google Sheets.
Chapter 1 Summary 🙌
Analytics programs allow businesses to access the untapped value locked within their data. Today, many organizations recognize the potential value of this work but are still in the early stages of developing their analytics programs. These programs, driven by the unprecedented availability of data, the rapidly decreasing cost of storage, and the maturation of cloud computing, promise to create significant opportunities for businesses and, in turn, for data professionals skilled in the tools and techniques of analytics.As analysts develop analytic work products, they generally move through a series of stages. Their work begins with the acquisition of data from internal and external sources and continues with the cleaning and manipulation of that data. Once data is in a suitable form, data professionals apply analytic techniques to draw conclusions from their data, create visualizations to depict the story of their data, and develop reports and dashboards to effectively communicate the results of their work to business leaders.

# Chapter 2 Understanding Data 
To understand data types, it is best first to understand data elements. A data element is an attribute about a person, place, or thing containing data within a range of values. Data elements also describe characteristics of activities, including orders, transactions, and events. Now that you understand what data elements are, let's explore how they relate to data types. A data type limits the values a data element can have.Pet Name, Animal Type, and Breed Name are all words. Meanwhile, the Date of Birth column contains numbers and slashes that identify a specific date. Height and Weight are both numbers. Each of these groupings represents a particular data type.
Tabular Data🐱‍👤🐱‍👤
Tabular data is data organized into a table, made up of columns and rows. A table represents information about a single topic. Each column represents a uniquely named field within a table, also called a variable, about a single characteristic. The contents of each column contain values for the data element as defined by the column header. The intersection of a row and column contains a specific value. Looking at the intersection of Jack and Breed Name in Table 2.1 tells us that Jack is a Corgi. If we want to identify Hazel's breed, we look at where her row intersects with the Breed Name column and see that she is a Labradoodle.Spreadsheets, including Microsoft Excel, Google Sheets, and Apple Numbers, are practical tools for representing tabular data. A relational database management system (RDMS), commonly called a database, extends the tabular model. Instead of having all data in a single table, a database organizes related data across multiple tables. The connection between tables is known as a relationship. Oracle, Microsoft SQL Server, MySQL, and PostgreSQL are examples of database software. Tabular data is the concept that underpins both spreadsheets and relational databases.
Structured Data Types🐬🐬
![image](https://github.com/matthew23-stack/DataAnalytics/assets/127289268/0e0d3780-0d06-45dd-8402-85c809c2d66d)
Structured data is tabular in nature and organized into rows and columns. Structured data is what typically comes to mind when looking at a spreadsheet. With clearly defined column headings, spreadsheets are easy to work with and understand. In a spreadsheet, cells are where columns and rows intersect.When you read the column headings, you get a good sense of the kind of data that you're going to find in that column. For example, when you see the “Weight (pounds)” column, you expect to see numeric values. In the Address field, you expect to see text. Looking more closely, we see that the data values are consistent for each column.
Character
The character data type limits data entry to only valid characters. Characters can include the alphabet that you might see on your keyboard, as well as numbers. Depending on your needs, multiple data types are available that can enforce character limits.Alphanumeric is the most widely used data type for storing character-based data. As the name implies, alphanumeric is appropriate when a data element consists of both numbers and letters.The alphanumeric data type is ideal for storing product stock-keeping units (SKUs). It is common in the retail clothing space to have a unique SKU for each item available for sale. If you sell jeans, you may stock products from Armani Jeans, Diesel, Lee Jeans, Levi's, and Wrangler. To keep track of all the manufacturer, size, color, and fit combinations in your inventory, you might use an SKU similar to the one depicted in Figure 2.2. Tracking inventory at the SKU level allows you to manage availability in your online and in-store systems, all courtesy of the alphanumeric data type.
![image](https://github.com/matthew23-stack/DataAnalytics/assets/127289268/c9f59bee-7905-46ab-aa7b-d21a48791d21)
There are times when it is necessary to impose even stricter limits on character-related data to exclude numbers. Excluding numbers can be achieved using the text data type.Consider a data entry example. Suppose you operate an online retail system. To deliver orders, you need address information for the intended recipients. This information comes from the customers themselves since they can specify where orders should be shipped.
Character Sets😁😁
When considering alphanumeric and text data types, you need to think about the character set you are using to input and store data when using a database. Databases use character sets to map, or encode, data and store it digitally. The ASCII encoding standard is based on the U.S. English alphabet. ASCII accommodates both the upper and lowercase English alphabet and numbers, mathematical operators, and symbols.Many languages include accent marks, extending the Latin alphabet. For example, Akrapovič is a Slovenian manufacturer. To store the č in Akrapovič, you need to encode that value appropriately. In addition, there are many languages, including Arabic, Chinese, Japanese, and Korean, which use symbols as opposed to extending the Latin alphabet. For example, the Arabic word for “cat.” Several encoding standards exist that accommodate non-Latin characters.
Numeric
When numbers exclusively make up values for a data attribute, numeric becomes the data type of choice. This data type appears to be simple and obvious based on its name. As seen with the character data type, implementation nuances about numeric are essential to understand. Databases accommodate two types of numeric data types: integer and numeric.
Whole Numbers
The integer, and all its subtypes, are for storing whole numbers. As seen with the character family of data types, implementation differences exist across databases. Table 2.3 illustrates how Oracle, Microsoft, and MySQL support whole numbers. Note that both the Microsoft and MySQL databases support the bit data type, which can be empty or store a 0 or a 1. In computer science, flags indicate whether something is on or off, or if a function has completed successfully. To show something is on, 1 or TRUE is used. For a value of off, 0 or FALSE is used. The bit data type is intended for storing the status of a flag. Note also that the value ranges for smallint and shortinteger are identical. The same is true for int and integer, as well as bigint and longinteger. Although the data types have different names, their functionality is equivalent.
Rational Numbers
In all its variants, the numeric data type is for rational numbers that include a decimal point. As with the integer family of data types, each database vendor has its implementation nuances. Table 2.4 illustrates how Oracle, Microsoft, and MySQL support rational numbers.
Date and Time
Gathered together under the broad category of date, day of year and time of day are data elements that appear with great frequency. As illustrated in Table 2.5, databases have various data types for handling date- and time-related information. As seen with character and numeric data types, nuances exist across different databases. Selecting the appropriate date-related data type depends on the data you need to store.
Currency
Many people use spreadsheets to manage their finances. Organizations typically use enterprise-scale software for the same purpose, with the data residing in a database. While financial data is numeric, people prefer seeing the numbers displayed as a specific currency. For example, consider the Number, Dollar, and Euro.
Strong And Weak Typing
Data types define values placed in columns. Strong typing is when technology rigidly enforces data types. Databases, discussed in Chapter 3, use strong typing. A database column defined as numeric only accepts numerical values. You will get an error if you attempt to enter characters into a numeric column.Weak typing loosely enforces data types. Spreadsheets use weak typing to help make it easier for people to accomplish their work. Spreadsheets default to an “automatic” data type and accommodate practically any value. When a person specifies a data type, it is loosely enforced compared to a database. For example, with a numeric spreadsheet cell, the software does not stop you from entering and storing characters.Software that uses weak typing can be helpful. That said, be mindful that you may experience unexpected and perhaps incorrect results.
Unstructured Data Types😏😏
While much of the data we use to record transactions is highly structured, most of the world's data is unstructured. Unstructured data is any type of data that does not fit neatly into the tabular model.Examples of unstructured data include digital images, audio recordings, video recordings, and open-ended survey responses. Analyzing unstructured data creates a wealth of information and insight. Many people have camera-enabled smartphones, and using video for conversations and meetings is commonplace.
Binary
Binary data types are one of the most common data types for storing unstructured data. It supports any type of digital file you may have, from Microsoft Excel spreadsheets to digital photographs. When considering which binary data type to use, file size tends to be the limiting factor. You need to select a data type that is as large as the largest file you plan on storing.
Audio
Audio data can come from a variety of sources. Whenever you interact with a customer service agent and hear “this call may be recorded for quality assurance purposes,” your conversation is probably being recorded and stored for later analysis. The impact of capturing, storing, and analyzing audio data has led to the development of avalanche detection systems. These systems listen for and detect the acoustic characteristics of an avalanche. With real-time notification capabilities, these systems reduce the time it takes for emergency services to respond and alert hikers to treacherous conditions.
Images
Image data can come from a variety of sources. People take more than 1 trillion photographs every calendar year, fuelled by the ubiquity of camera-enabled smartphones and relatively low storage costs. Each digital picture is a piece of unstructured data. 
Video
Video data is growing at a similar pace to image data. In the consumer space, people upload videos to YouTube, Instagram, and TikTok every day. Police officers wear body cameras to create a video record of enforcement situations. Image processing algorithms examine videos to detect everything from traffic congestion to intruders in the home.
Categories of Data😴😴
We try to fit data into structured and unstructured categories. The reality is that the world is not black and white, and not all data fits neatly into structured and unstructured categories. Semi-structured data represents the space between structured spreadsheets and unstructured videos.
Quantitative vs. Qualitative Data
Regardless of structure, data is either quantitative or qualitative. Quantitative data consists of numeric values. Data elements whose values come from counting or measuring are quantitative.
Discrete vs. Continuous Data
Numeric data comes in two different forms: discrete and continuous. A helpful way to think about discrete data is that it represents measurements that can't be subdivided. You may intuitively think of discrete data as using whole numbers, but that doesn't have to be the case. For example, if a fundraising organization sells chickens in half-chicken increments, you can buy 1.5 chickens. However, you can't buy .25 chickens.
Categorical Data
In addition to quantitative, numeric data, there is categorical data. Text data with a known, finite number of categories is categorical. When considering an individual data element, it is possible to determine whether or not it is categorical. Let's continue to identify each data element of the pet dataset in Table 2.1. Animal Type is a good example of categorical data. As represented, this column separates the data into two categories: dog and cat. As additional dogs or cats enter into care, they fall within the existing categories.
Dimensional Data
Dimensional modeling is an approach to arranging data to facilitate analysis. Dimensional modeling organizes data into fact tables and dimension tables. Fact tables store measurement data that is of interest to a business. A veterinary practice may want to answer some questions about appointments. A table holding appointment data would be called a fact table. Dimensions are tables that contain data about the fact.
Common Data Structures🤖🤖
In order to facilitate analysis, data needs to be stored in a consistent, organized manner. When considering structured data, several concepts and standards inform how to organize data. On the other hand, unstructured data has a wider variety of storage approaches
Structured Data💀💀
Tabular data is structured data, with values stored in a consistent, defined manner, organized into columns and rows. Data is consistent when all entries in a column contain the same type of value. This method of organization facilitates aggregation. For example, you can add each value in the Weight column in Table 2.1 to get the total weight for all animals.
![image](https://github.com/matthew23-stack/DataAnalytics/assets/127289268/c6374470-6073-45a5-9c3b-4e756e9beed1)
