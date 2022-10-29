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

3.  
