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

# TASK TWO :

Scope : A laptop has been flagged up on our security systems due to suspicious internet traffic, and we need you to investigate the network traffic in order to establish what the user accessed and downloaded.
Your task is to examine their network activity and gather what information you can on what images they viewed and what files they accessed.

# Objective :

You have been provided with a packet capture file (pcap) containing all their recent network activity. There may be a number of artifacts contained within the packet capture file, and you will be expected to identify and report as many as possible.

# Tools Used
<div>
    <img src="https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white" />
    <img src="https://img.shields.io/badge/-HxD_Hex_Editor-800080?&style=for-the-badge" alt="HxD Hex Editor" />
    <img src="https://img.shields.io/badge/-Cyber_Chef-33CC33?&style=for-the-badge" alt="Cyber-Chef" />
</div>

# Steps :

The first thing i did was load up the PCAP file into Wireshark and this is the initial information you get when you open the file 

![Screenshot 2025-07-09 160625](https://github.com/user-attachments/assets/36c10a98-01f2-47f5-8338-9b18b9e12756)

There was nothing to it here, so i decided to put “http” into the filter field in order to filter the network traffic to only see HTTP packets. 

![http](https://github.com/user-attachments/assets/26827139-52d6-4efb-96c3-14194f5f3f8f)

This view let me see some interesting http GET requests, which indicate that the user specifically requests information.

![Screenshot 2025-07-05 090538](https://github.com/user-attachments/assets/47c14ec1-9fe8-4ec3-ab5d-083c9be8e772)

To investigate this image download further, I viewed its TCP stream to see what I could find. Looking through the data in the TCP stream showed that this get request downloaded two images

![steps](https://github.com/user-attachments/assets/28508db2-d6f5-4e62-982e-622286f532c4)

I was then presented with the following data and decided to change the format of the data from ASCII to Raw, this would allow me to see the magic numbers or file signatures (These are specific sequences of bytes (often hexadecimal) found at the very beginning of a file. They act as a unique identifier or "fingerprint" that tells an operating system or application what type of file it is ) of the file to be able to extract it.

![ASCIIP2](https://github.com/user-attachments/assets/c45ac27d-109e-4093-8952-0a8db71c1028)

This is the the file after it was formated to present the data in its Raw format.

![Screenshot 2025-07-09 163308](https://github.com/user-attachments/assets/abfda80e-2135-4ce7-8fc2-fad53861187b)

i noticed that at the top of the file there was a get request for a jpg file. From here i then went to the following website (https://filesig.search.org/) to try and figure out what the file signature of a jpg file could be, and i found the following :

![Screenshot 2025-07-09 164725](https://github.com/user-attachments/assets/b4bc61c0-8410-4c4d-b1a2-6f552d77622a)

Once i had the header/footer of the file confirmed ( FFD8 – FFD9 ) i then searched these signatures :

![ffde8](https://github.com/user-attachments/assets/d7f55eb3-4d68-4af1-9f6e-c6443a04627c)

I then copied the values from the header to the footer and took the copied information and pasted it into HxD Hex Editor 

![HxD3](https://github.com/user-attachments/assets/cdc89105-97af-4ff7-bb35-8c0437be5ca0)

From here i saved the file as a jpg file and found out that the following image was the one viewed :

![ANZ-logo](https://github.com/user-attachments/assets/8ae57e7c-ddb9-4721-ae81-d85a37475426)

I then followed the steps that i took to get the image mentioned above and found the following images as well :

![bank-card](https://github.com/user-attachments/assets/6a72342f-5c03-4cdd-a903-4b21db4a35fc)
![ANZ1](https://github.com/user-attachments/assets/258b9015-e1ff-44b9-a641-c3fc34c5ff95)
![ANZ2](https://github.com/user-attachments/assets/8eade859-d283-4e44-a88c-2d76955ae58e)

When filtering the http get request i noticed that one of the requests was for a .docx file and discovered that there is no file signature for this specific type of file so i followed the TCP stream and changed the format into ASCII and found the following message :

![Message](https://github.com/user-attachments/assets/c4fec112-a6ef-4a39-9400-8437cedc07e0)

The steps that followed were a repetition of the steps i took in getting the first couple of images except  for this i had to get the file signature for the pdf. Upon research i discovered that there's are “25 50 44 46” and “25 25 45 4F 46” with “25 50 44 46” signifying the beginning of the file and “25 25 45 4F 46” showing the end of the file. 

So following the steps mentioned i managed to extract the following: 

![1](https://github.com/user-attachments/assets/3b524967-1242-403a-9d03-97436595ea98)
![2](https://github.com/user-attachments/assets/83e32a62-dc1b-4c08-9c15-63ac962fbd3a)
![3](https://github.com/user-attachments/assets/064d0205-490f-4afb-af04-5b8b03c54c36)

There is no distinct file signature of a .txt file and came across a bit of a problem, so i had a look at the file in its raw format and found out that this was in fact a .jpg file so i did the steps that i mentioned below and found the following : 

![hidden](https://github.com/user-attachments/assets/43c3c260-eaa6-4db0-ac12-2b894d007ba8)

In this get request, the raw data had something in particular stood out for me, after the immediate end of the image i was extracting i found the file signature of another image and i traced it to the end and found out that there is infact two images that i was supposed to get and these are the images that i got : 

![atm](https://github.com/user-attachments/assets/93ae4539-456d-4c66-ae7a-1b7edf72ffe5)
![image 2](https://github.com/user-attachments/assets/95925020-1d4a-469d-890a-c4cfb001b7c2)

The TCP stream for the broken.png traffic did not show any file signature for a png image. So while viewing the ascii form of the data, I recognized that the data was encoded in base64. So i used the Cyber Chef tool and that gave me the following png image data :
![ANZ 1](https://github.com/user-attachments/assets/fb6cc516-6532-480f-a2ff-a2a401a82810)

After investigating the TCP stream for securepdf.pdf I found the following :
- The data there was not for a PDF.
- The bottom of the file contained the hidden message: Password is “secure”
![secure](https://github.com/user-attachments/assets/f70e3aed-a478-4a53-8978-7c9066cefe29)

i went back to the GaryKessler website and found that the following file signature was for a ZIP file. So I copied the hex of the zip file into Cyber Chef and saved it as a zip file. I opened this zip file, and found it contained a pdf file called rawpdf.pdf. When opened, the pdf asked for a password. The password ‘secure’ shown in the tcpbstream worked, and the PDF opened. It was the first two pages to a guide for internet banking and here are the images of the file :

![Screenshot 2025-07-09 174200](https://github.com/user-attachments/assets/7567a496-191a-4bb5-9562-b1d5b3293436).

# Conclusion :
This brings the job simulation to an end, upon this i was provided with a certification of completion and can confidently say that i am compitent in the following :

- Investigate e-mails to report suspicious items
- Analyse a Packet Capture file using an open source tool to identify and investigate any potential threats

<a href="https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/AKkAyEwWc8wjPxx9n/Hf4QMESoFeQwXPsiH_AKkAyEwWc8wjPxx9n_mvw8oKQbrDajKM8Sh_1751703320907_completion_certificate.pdf" target="_blank">
  <img src="https://img.shields.io/badge/-ANZ-0066CC?&style=for-the-badge" alt="ANZ Project Certificate" />
</a>






