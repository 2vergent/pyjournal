# pyjournal

* pyJournal, a Diary app, is written in python.
* It maintains all your journal entries in a neat way 
  which can be accessed by you anytime.
* With just a few commands to remember, it can't get easier than this.

* There are three profiles:
	1. @Root:     This profile is used to login or signup
	2. @xxxx:     This profile is created when you login and xxxx is replaced by your username
        3. edit@xxxx: This profile is used to add/delete entries

* Commands for @root:
	1. login:  Login to your journal and start making entries
	2. signup: Signup for a new journal
	3. clear:  Clears the screen. Trust me, you might use this a lot
	4. kill:   Quits pyjournal instantly

* Commands for @xxxx:
	1. entry: Adds a new entry to your journal for the day
	2. check: Asks for a date to check previous entries in your journal
	3. root:  Switches back to @root profile
        4. edit:  Edit previous entries
	5. list:  Lists all your entries based on months and days
        6. edit:  Enters into Journal edit mode
	6. clear: Clears the screen
	7. kill:  Quits pyJournal instantly

* Commands for edit@xxxx:
        1. add:   Adds an entry under any date specified
        2. del:   Deletes entry(s) from a Journal
        3. @xxxx: Go back to your user profile(@xxxx)
        4. root:  Goes back to root
        5. clear: Clears the screen
        6. kill:  Quits pyJournal instantly
        * You can delete multiple entries by giving entry numbers separated by commas
          Example: 4,5,7

* In any of the profiles, you can type "help" to get the above information displayed
