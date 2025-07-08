# ANZ-Forage-Simulation
In this simulation i was provided with two tasks. The first task was Analysing a bunch of Emails to see if they were phising attempts or not and the second task was to Analyse a PCAP file and draw out information from it. 

Before i get in to how i did this, id like to express that these resouces that you will get a glimpse of are provided by forage.

# TASK ONE:

Scope : You have been assigned 7 emails to investigate. Some of these emails may contain content which can be classed as malicious, due to a number of reasons. They may contain malicious attachments, suspicious links, or Phishing attempts to gather private account information from the user.

# Obejective:

Review selected emails and report findings on whether each is safe or malicious.

![Screenshot 2025-07-07 233856](https://github.com/user-attachments/assets/2a1c7526-a529-470e-bc29-1008d87ebfc1)

# Steps
- The first thing that i did was scan the email header to check if there was anything suspicious with the senders email ( the domain ).
- Second whilst staying on the header i checked if the email address matches the name of the sender.
- lastly i did a quick scan of the email to check if there is any suspicious links or attachments to the email.
  
# Conclusion
This Email is safe

My analysis :

- There seems to be no attachments to the email. 

- No Malicous links that have spotted. 

- The E-mail address corresponds with the name of the sender. 

- Informal tone used( such as “mate” and “Sick as!!”), suggests a friendly conversation between two people. 

- The use of “FYI” signifying that there is a level of urgency in this conversation between them but not one to pressure anyone into doing something almost like a reminder of sorts.

![Screenshot 2025-07-08 101044](https://github.com/user-attachments/assets/268227d7-2cf5-4888-b00f-f9e3367f5ef6)

# Steps
- The first thing that i did was scan the email header to check if there was anything suspicious with the senders email ( the domain ).
- Second whilst staying on the header i checked if the email address matches the name of the sender.
- lastly i did a quick scan of the email to check if there is any suspicious links or attachments to the email.

# Conclusion
This Email is Malicious

My analysis :

- The domain is from Russia( the header states “Venture.ru” the ru in the case shows it is in fact from Russia), 

- There is an urgency, almost to pressure the reciever into taking immediate action to act. 

- There is a hyperlink attached to the E-mail which could potentialy lead to a malicous website. 

- The E-mail claims to be from OneDrive a miscrosoft divison but mentions Adobe PDF which has nothing to do with Microsoft.

![Screenshot 2025-07-08 101534](https://github.com/user-attachments/assets/8417a593-061d-4bea-8e09-f2effcf8d238)

# Steps
- The first thing that i did was scan the email header to check if there was anything suspicious with the senders email ( the domain ).
- Second whilst staying on the header i checked if the email address matches the name of the sender.
- lastly i did a quick scan of the email to check if there is any suspicious links or attachments to the email.

# Conclusion
This Email is Malicious

My analysis :

- There is a link attached to the E-mail, upon further inspection the Link seems to have a typo instead of a B in the term Facebook, there is a  “ß“ which hints to this being a malicous link. I ran a list of valid Facebook domains and non of them have the character above, confirming the theory that it is a malicous link

![Screenshot 2025-07-08 101805](https://github.com/user-attachments/assets/7d7bfc95-06e0-4b72-b679-a440ba7d3be3)

# Steps
- The first thing that i did was scan the email header to check if there was anything suspicious with the senders email ( the domain ).
- Second whilst staying on the header i checked if the email address matches the name of the sender.
- lastly i did a quick scan of the email to check if there is any suspicious links or attachments to the email.

# Conclusion
This Email is Safe

My analysis :

- There is no attached links. 

- Seems to be an mass advertisement email.  

- The original E-mail seems has been verified at Hunter.io and seems to be a valid E-mail.

![Screenshot 2025-07-08 102254](https://github.com/user-attachments/assets/f4d77d8a-d233-4868-b0bc-cbcd908784d2)

# Steps
- The first thing that i did was scan the email header to check if there was anything suspicious with the senders email ( the domain ).
- Second whilst staying on the header i checked if the email address matches the name of the sender.
- lastly i did a quick scan of the email to check if there is any suspicious links or attachments to the email.

# Conclusion
This Email is Malicious

My analysis :

- Sender Claims to be undercover FBI agent.That already rings alarms because they are also disclosing what should be classified as private information. 

- Sender says they require to use the E-mail to send information so they require access to E-mail. This would mean that even in the country the IP address would change hence making it unusuable still according to their logic. 

- Sender Created a huge sense of importance to try and pressure the sender to act promptly.

![Screenshot 2025-07-08 102621](https://github.com/user-attachments/assets/2f24090e-ce39-464d-a921-a12d114dbca0)

# Steps
- The first thing that i did was scan the email header to check if there was anything suspicious with the senders email ( the domain ).
- Second whilst staying on the header i checked if the email address matches the name of the sender.
- lastly i did a quick scan of the email to check if there is any suspicious links or attachments to the email.

# Conclusion
This Email is Safe

My analysis :

- No sight of any attachements to the E-mail, no links or files included. 

- Seems to be a conversation between two employees and both of them with the same domain of “@anz.com” 

- The strcuture and format of the E-mail seems to be professinally made as well hinting at a proper well established business email template 

![Screenshot 2025-07-08 102824](https://github.com/user-attachments/assets/c2d3bbfe-9654-41fa-bcbf-8cbd80cfbdb2)

# Steps
- The first thing that i did was scan the email header to check if there was anything suspicious with the senders email ( the domain ).
- Second whilst staying on the header i checked if the email address matches the name of the sender.
- lastly i did a quick scan of the email to check if there is any suspicious links or attachments to the email.

# Conclusion
This Email is Malicious

My analysis :

- Just a suspicous link attched. 

- Even if link was valid, it still the URL starts with “hxxp” showing it has been obfuscated to indicate that its been changed. 

- The obfuscated link also is not secure as it lacks the “s” that is used to show a secure protocol is in use. 

- The email could potentially be from Morocco 




