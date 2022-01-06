# How to Send Email using Waston Assistant

I think this topic is worth to be communicate if we are doing some project using Waston Assistant. I and my groupmates try to built a chatbot in the waston assistant, because this chatbot is for our customer, a property company, to collect their customer information when their customers communicate with the chatbot and agree leave their information for the company to connect them.

However, after the chatbot was built, we meet a problem. How to send an email using waston assistant which contain the customer information they leave ?

We find an article talking about this. "Send e-mails from Watson Assistant using IBM Cloud Functions" from Isa Torres is very useful. I would attach the web link.(https://medium.com/@isamarietr/send-e-mails-from-watson-assistant-using-ibm-cloud-functions-e8921a4d8cd2)

In a word, if we can follow this whole article, everything would be okay. But there are some details need to be noticed.

## API Key

<img width="553" alt="image-20220106142349996" src="https://user-images.githubusercontent.com/66622896/148342542-d92de7ae-42c7-4551-b6e6-4d898095d737.png">


This is API key part in the article. But there may be some different now. I think If you open the function interface or actions form function interface, you would see the current namespace, but the key part is not in the same place. Every namespace would have only one API key. 

<img width="632" alt="2022-01-06 (1)" src="https://user-images.githubusercontent.com/66622896/148342674-5598a8ad-207d-4288-b662-d3fd69028314.png">



The API key for the namespace is in the red line part - Namespace Setting.

<img width="955" alt="2022-01-06 (3)" src="https://user-images.githubusercontent.com/66622896/148342643-072d2395-5313-4199-bda5-00bed105fe1b.png">


This API Key is the part we really needed



