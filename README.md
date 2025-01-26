# Project Name
> Prompt Engineering - Develop a Travel Planner AI chatbot that assists travellers in planning their trips. It can recommend top hotels and suggest itineraries based on user-specified destinations.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Goal is Develop a Travel Planner AI chatbot that assists travellers in planning their trips.
- The program provides instructions using chain of thought and few shot prompting techniques
- The primary role of the chatbot is finding appropriate hotels in the provided locality
- I have described the process within prompts, prompting the model to output a JSON object containing arguments. This JSON can then be used to call those functions in the code. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- See the sample conversation
-
- Starting conversation with your Travel Planner...
-
- Hi, whom am I talking to?
- Rishi
-
- Your Travel Planner:
- Welcome Rishi
- I understand you are looking for hotel. Our automated travel planner will help you. If travel planner is taking time to provide the recommendations, please be patient and provide a reminder periodically.
-
- Your Travel Planner: 
- I am glad to assist you in finding the perfect hotel. To get started, could you please provide me with the following information:
- 1. Destination city or area?
- 2. Check-in and check-out dates?
- 3. Number of guests (adults and children)?
- 4. Room preferences (e.g., single room, double room, suite)?
- 5. Specific amenities you are looking for (e.g., pool, gym, free breakfast)?
- 6. Travel purpose (business or pleasure)?
- 7. Budget per night?
-
- Rishi:
- Coorg from 11th Sept to 13th Sept
-
- Your Travel Planner: 
- Great choice! I can help you find the perfect hotel in Coorg. Could you please provide the following information:
- 1. Number of guests (adults and children)?
- 2. Room preferences (e.g. single room, double room, suite)?
- 3. Specific amenities you are looking for (e.g. pool, gym, free breakfast)?
- 4. Budget per night?
- 5. Are you traveling for business or pleasure?
-
- Rishi:
- 2 adults and 2 children
- 
- Your Travel Planner: 
- Thank you for providing that information. 
- Would you prefer a single room, double room, or a suite? Also, do you have any specific amenities you are looking for in the hotel?
- 
- Rishi:
- suite with breakfast
-
- Your Travel Planner: 
- Thank you for providing that information. What is your budget per night for the hotel in Coorg?
- 
- Rishi:
- Rs. 15000 per night
-
- Your Travel Planner: 
- Thank you for providing that information. Are you travelling for business or pleasure?
-
- Rishi:
- pleasure
-
- System: Thanks for the information. Here is what you requested
- {'destination': 'Coorg', 'check-in date': '11th Sept', 'check-out date': '13th Sept', 'number of guests': 4, 'room prefernce': 'suite', 'amenities': 'breakfast', 'budget': 15000}
-
- Your Travel Planner: 
- Thank you for providing that information. Since you are traveling for pleasure, would you like me to suggest an itinerary for your trip to Coorg between 11th Sept to 13th Sept?
-
- Rishi:
- yes
-
- Your Travel Planner: 
- Great! I have all the information I need to find the perfect hotel for you in Coorg.
-
- Rishi:
- itinerary
- 
- Your Travel Planner: 
- Great! Here are the top 3 hotel options in Coorg for your stay from 11th Sept to 13th Sept:
-
- 1. Hotel Aroma: 
   - Rate per night: Rs. 12,000
   - Area: Central Coorg
   - Room type: Suite with breakfast
   - Total Hotel Price for 2 nights: Rs. 24,000
-
- 2. Hilltop Resort:
   - Rate per night: Rs. 14,000
   - Area: Serene Coorg Valley
   - Room type: Suite with breakfast
   - Total Hotel Price for 2 nights: Rs. 28,000
-
- 3. Riverside Retreat:
   - Rate per night: Rs. 13,000
   - Area: Alongside the river
   - Room type: Suite with breakfast
   - Total Hotel Price for 2 nights: Rs. 26,000
-
- Since you mentioned you are traveling for pleasure, here is a suggested itinerary for your stay in Coorg:
-
- Day 1: 
- Arrive in Coorg and check-in at your hotel
- Visit the Dubare Elephant Camp
- Enjoy a relaxing evening near the river at your hotel
-
- Day 2:
- Explore Abbey Falls and take a nature walk in the surrounding coffee plantations
- Visit the Madikeri Fort in the afternoon
- Enjoy a traditional Coorgi dinner in the town
-
- Day 3:
- Visit the Namdroling Monastery and witness the beautiful Tibetan architecture
- Spend the afternoon exploring the local markets for souvenirs
- Check-out from the hotel and depart from Coorg
-
- Enjoy your trip to Coorg!
-
- Rishi:
- exit
- 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was part of our learning for ML C56
- The project was worked by Rishi


## Contact
Created by [@rishiash] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
