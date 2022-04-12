# AWS-Services-LexBot
I had created a lex bot in Amazon Web Services(AWS)<br>
In this we had used the following services:-
   > Lambda (for applying inilizations and validations)<br>
   > Amazon Lex<br>
   > Cloudwatch (for resolving errors)<br>

We had created this LexBot in N.Virginia<br>

## First we will create the LexBot in Amazon Lex
1.) Login in to your AWS account and in the search box type Amazon Lex<br>
2.) After clicking on Lex, click on GetStarted <br> 
![img1](https://user-images.githubusercontent.com/53809138/162933695-282b25b2-2a82-41fb-a513-f2f1d458f8f1.jpeg)
3.) Now click on Create Bot<br>
![img2](https://user-images.githubusercontent.com/53809138/162936284-0a9870e3-a74a-4c7f-a338-4001916ff463.jpeg)
4.) Click on Custom Bot<br>
5.) Enter the name for your Bot<br>
6.) Choose your Bot Language (ENGLISH(IN))<br>
7.) Choose Ouput for your Bot<br>
8.) Choose Session TimeOut <br>
9.) IAM remains same<br>
10.) Choose COPGA to NO <br>
11.) Leave empty Confidence score threshold <br>
![Screenshot (11)](https://user-images.githubusercontent.com/53809138/162937850-76290389-6a15-43ba-989a-6f075ab1df15.png)
<b> Now Click on Create <br>
## Creating Intent and Slot types
   ![img3](https://user-images.githubusercontent.com/53809138/162938027-12419f79-b124-4d5e-ae52-c755b18c002b.png)
- Click on create Intent and give intent a unique Name<br>
- Write Some 'Sample Utterances' for the customer to ask questions in different manners<br>
- Enter Slot Values to ask question for the customer<br>
- Enter response in the response card<br>
- You can add confirmation Prompt (Optional) if needed<br>
