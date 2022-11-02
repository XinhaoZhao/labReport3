1.  find lines in a file that contain certain strings  
```
C:\Users\acer\Downloads\technical\911report>find "shot down" chapter-1.txt

---------- CHAPTER-1.TXT
    Minutes went by and word arrived of an aircraft down in Pennsylvania. Those in the shelter wondered if the aircraft had been shot down pursuant to this authorization.
    NORAD officials have maintained that they would have intercepted and shot down United 93. We are not so sure. We are sure that the nation owes a debt to the passengers of United 93. Their actions saved the lives of countless others, and may have saved either the Capitol or the White House from destruction.
```
```
C:\Users\acer\Downloads\technical\911report>find "colleagues" chapter-1.txt

---------- CHAPTER-1.TXT
    In another Logan terminal, Shehhi, joined by Fayez Banihammad, Mohand al Shehri, Ahmed al Ghamdi, and Hamza al Ghamdi, checked in for United Airlines Flight 175, also bound for Los Angeles. A couple of Shehhi's colleagues were obviously unused to travel; according to the United ticket agent, they had trouble understanding the standard security questions, and she had to go over them slowly until they gave the routine, reassuring answers.
    The security checkpoints through which passengers, including Atta and his colleagues, gained access to the American 11 gate were operated by Globe Security under a contract with American Airlines. In a different terminal, the single checkpoint through which passengers for United 175 passed was controlled by United Airlines, which had contracted with Huntleigh USA to perform the screening.
    Shortly thereafter, the passengers and flight crew began a series of calls from GTE airphones and cellular phones. These calls between family, friends, and colleagues took place until the end of the flight and provided those on the ground with firsthand accounts. They enabled the passengers to gain critical information, including the news that two aircraft had slammed into the World Trade Center.
    At least ten passengers and two crew members shared vital information with family, friends, colleagues, or others on the ground. All understood the plane had been hijacked. They said the hijackers wielded knives and claimed to have a bomb. The hijackers were wearing red bandanas, and they forced the passengers to the back of the aircraft.
    At 10:02 that morning, an assistant to the mission crew commander at NORAD's Northeast Air Defense Sector in Rome, New York, was working with his colleagues on the floor of the command center. In a brief moment of reflection, he was recorded remarking that "This is a new type of war."
```
```
C:\Users\acer\Downloads\technical\911report>find "colleagues" chapter-2.txt

---------- CHAPTER-2.TXT
                Bin Ladin and his al Qaeda colleagues. By the late 1980s, the Egyptian Islamist
```
2. find /C: returns the count of lines containing the input string  
```
C:\Users\acer\Downloads\technical\911report>find /C "colleagues" chapter-2.txt

---------- CHAPTER-2.TXT: 1
```
```
C:\Users\acer\Downloads\technical\911report>find /C "the" chapter-2.txt

---------- CHAPTER-2.TXT: 526
```
```
C:\Users\acer\Downloads\technical\911report>find /C "is" chapter-2.txt

---------- CHAPTER-2.TXT: 368
```
3. find /i: specify that the search is case insensitive.  
```
C:\Users\acer\Downloads\technical\911report>find /i "FAMILY" chapter-2.txt

---------- CHAPTER-2.TXT
                existed or was quickly established under a paramount tribal family. Monarchies in
                often obtained at the cost of great family sacrifice, and blocked from starting
                family's huge fortune. Though he took part in at least one actual battle, he became
                member of the royal family, he managed to get out of the country under the pretext
                normal costs of doing business increased. Saudi pressures on the Bin Ladin family
            He was accompanied by family members and bodyguards, as well as by al Qaeda members
```
```
C:\Users\acer\Downloads\technical\911report>find /i "DISPLAY" chapter-3.txt

---------- CHAPTER-3.TXT
                on display than in the case of Pan American Flight 103, bound from London to New
```
```
C:\Users\acer\Downloads\technical\911report>find /i "DISPLAY" chapter-1.txt

---------- CHAPTER-1.TXT
    Shortly after the first call, Barbara Olson reached her husband again. She reported that the pilot had announced that the flight had been hijacked, and she asked her husband what she should tell the captain to do. Ted Olson asked for her location and she replied that the aircraft was then flying over houses. Another passenger told her they were traveling northeast. The Solicitor General then informed his wife of the two previous hijackings and crashes. She did not display signs of panic and did not indicate any awareness of an impending crash. At that point, the second call was cut off.
    On 9/11, the terrorists turned off the transponders on three of the four hijacked aircraft. With its transponder off, it is possible, though more difficult, to track an aircraft by its primary radar returns. But unlike transponder data, primary radar returns do not show the aircraft's identity and altitude. Controllers at centers rely so heavily on transponder signals that they usually do not display primary radar returns on their radar scopes. But they can change the configuration of their scopes so they can see primary radar returns. They did this on 9/11 when the transponder signals for three of the aircraft disappeared.
    The failure to find a primary radar return for American 77 led us to investigate this issue further. Radar reconstructions performed after 9/11 reveal that FAA radar equipment tracked the flight from the moment its transponder was turned off at 8:56. But for 8 minutes and 13 seconds, between 8:56 and 9:05, this primary radar information on American 77 was not displayed to controllers at Indianapolis Center.
    At 10:02, the communicators in the shelter began receiving reports from the Secret Service of an inbound aircraft-presumably hijacked-heading toward Washington. That aircraft was United 93. The Secret Service was getting this information directly from the FAA. The FAA may have been tracking the progress of United 93 on a display that showed its projected path to Washington, not its actual radar return. Thus, the Secret Service was relying on projections and was not aware the plane was already down in Pennsylvania.
```
            
