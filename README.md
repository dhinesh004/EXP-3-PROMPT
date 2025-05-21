# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

Scenario: Resolving Wi-Fi Connectivity Issues with a Smart Device 

Product: Smart Thermostat Pro 

User Issue: "My Smart Thermostat Pro isn't connecting to my Wi-Fi." 

Chatbot Interaction: 

1.	Straightforward Prompt (Initial User Query):
2.	
•	User: "My Smart Thermostat Pro isn't connecting to my Wi-Fi."

•	Internal Prompt to AI: "The user is reporting a Wi-Fi connectivity issue with the Smart Thermostat Pro. Acknowledge the issue and offer initial basic troubleshooting." 

•	Chatbot Response: 
"Hi there! I understand your Smart Thermostat Pro is having trouble connecting to your WiFi. Let's try to get this sorted out. Have you tried restarting your thermostat and your Wi-Fi router?" 

4.	Preceding Question Prompting (Gathering Specific Details):
   
•	User: "Yes, I've restarted both, but it's still not connecting." 
•	Internal Prompt to AI: "The user has already tried restarting. Ask a preceding question to gather more specific information about the Wi-Fi setup." 
•	Chatbot Response: 
"Okay, thanks for trying that. To help me understand better, could you please tell me the name (SSID) of your Wi-Fi network and whether you are using a 2.4 GHz or 5 GHz network?" 

6.	User Provides Information: 
•	User: "My Wi-Fi name is 'HomeNet' and it's a 2.4 GHz network."

7.	Tabular Format Prompting (Delivering a Structured Troubleshooting Guide): 
•	Internal Prompt to AI: "The user's Wi-Fi network is 'HomeNet' (2.4 GHz).
 Generate a step-by-step troubleshooting guide in a numbered list format focusing on 2.4 GHz connectivity issues for the Smart Thermostat Pro." 
 
•	Chatbot Response: "Thanks for that information. Here's a step-by-step guide to try connecting your Smart Thermostat Pro to your 'HomeNet' (2.4 GHz) Wi-Fi 
 
STEP 	ACTION 	EXPECTED OUTCOME 

Check Wi-Fi Password 	Ensure you are entering the correct password for 'HomeNet'. 
Double-check for typos and capitalization. 	
The thermostat should attempt to connect if the password is correct. 
Bring Thermostat Close 	Temporarily move the thermostat closer to your Wi-Fi router to rule out signal strength issues 	 If it connects when closer, the original location might have a weak signal. 
Forget and Reconnect 	On the thermostat's settings menu, try forgetting the 'HomeNet' network and then attempt to reconnect. 	This can sometimes resolve temporary 	connection glitches.  
 
Check Router Settings 	 Ensure your router is broadcasting the 2.4 GHz band and that MAC address filtering (if enabled) isn't blocking the thermostat 	 You might need to access your router's configuration page 
Restart Thermostat (Again) 	After making any router changes, restart the Smart Thermostat Pro. 	This ensures the thermostat picks up the new settings 


### Algorithm:  1. Direct Instruction Prompts
Objective: Guide the chatbot to respond concisely to customer inquiries.
Prompt Pattern:
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"

2. Contextual Prompting
Objective: Incorporate specific context to provide detailed answers based on the user’s previous interaction.
Prompt Pattern:
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"

4. Persona-Based Prompting
Objective: Design the chatbot to adopt a specific persona, making the interaction more engaging.
Prompt Pattern:
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"

6. Few-Shot Prompting
Objective: Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.
Prompt Pattern:
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"

8. Chain of Thought Prompting
Objective: Use a step-by-step reasoning approach for resolving more complex or technical issues.
Prompt Pattern:
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"

10. Instruction with Constraints
Objective: Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).
Prompt Pattern:
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"

12. Reflective Prompting
Objective: Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.
Prompt Pattern:
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
Result: The various types of Prompts are executed successfully.




# Result: Thus the Prompts were exected succcessfully .

