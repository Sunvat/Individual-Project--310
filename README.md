# Individual Assignment-310
## A brief introduction to the project:
<br>
The project is a simple and friendly chat-bot with which the user can talk about their hobbies, interests etc.  We are using the chat bot as a friend but in most cases these days these bots are used for customer service. Keeping in mind the recent pandemic and how it has changed everyone’s social lives. A virtual “friend” is able to make normal conversations and allows the user to chat to this bot anytime and share their experiences when their friends are busy or for the people who have a hard time socialising.
<br>

 ---
 ## Added Features after A3:
 |Feature|Explanation|
 |---|---|
 |Google Translate API|The google translate API uses real time translation of the texts that are input by the user in this project the language converted to is French.|
 |GUI|An improved GUI which makes the user feel more comfortable making conversations with the Bot.|
 |Static Maps API|The static maps API is a google api which allows the developers to integrated maps into the java appication.|
 
 ---
 
 ## Added Java Files:
 1. **Translate.java** : This is the java file which the bot uses to convert the text from the user to another language, in this case french. The file basically works as follows, it takes the google translate API, opens a new connection using URL library. Uses the text from user as value which is to be passes as parameters i.e. the parameter that has to be translated. The method called "translate" gets two more parameters called src for source and tar for target which are defined as "en"(english) and "fr" for French respectively. Meaning that the english sentence which is input will be translated to French and returned as an output by the method which then will be tranferred to the ChatBot class which will display the result.

 2. **StaticGoogleMap.java** : The java file allows the developer to embed a static map into the java application such as this chat bot. It incorporates the usage of maps into the chat bot to make it more interactive as the user can zoom in and out of places, look at different styles of maps. 
 
 ---
 
 
 ## Chosen SDLC: Waterfall Model
 
The software development cycle that we decided to work on is the waterfall model as for small deliverable projects waterfall model is convenient. As we are developing a small chat-bot whose requirements are clear, the project is short and simple, waterfall model seemed like a good fit for this project. This model is also very easy to understand as the steps are straightforward and avoids any confusion as it takes a more linear approach to the completion of the project.<br>
On the other hand, this model does slow down the process as the team needs to complete a step before moving on to the next one which often overlooks revision or any unexpected errors.

**WATER-FALL MODEL:**
1. PLANNING:
   -	Requirements
   - Project scope.
2.	DESIGN:
    -	User-friendly design
    -	User approval
    - Revision
3.	IMPLEMENTATION:
    - Developing phase
    -	Error-Handling
4. DEPLOYMENT:
5. MAINTAINENECE

---


---
## Data Flow Diagrams

# Current DataFlow Diagram with Added APIs:

The updated data flow diagram shows the new APIs that have been added to the chat bot appication.

<img src = "https://github.com/Sunvat/Individual-Project--310/blob/main/images/final_dfd.png" width = "50%" height = "50%">



### Data Flow Diagram for Level 0:
<img src = "https://github.com/aaliazoya/COSC-310-Assignment2/blob/main/images/Data%20Flow%20Diagram%20level%200%20.png" width="50%" height="50%">

<br>

## Data Flow Diagram for Level 1:

<img src = "https://github.com/Sunvat/Individual-Project--310/blob/main/images/Data%20Flow%20Diagram%20level%201%20(1).png" width="50%" height="50%">
