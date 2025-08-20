# Kill Team Tac Ops Tracker

This simple, single-page tracker is for playing the tabletop game **Kill Team (24)**. It's designed to be used on your phone (though can be used on a computer), helping to reduce table clutter by moving the tracking of Tac Ops, Crit Ops, and other game stats to a digital format that can be tucked into your pocket while playing. 

### Key Features
* **Select your Mission**: The tracker allows you to choose the **Crit Op** for your current game. All cards are visible to begin with. After choosing a Mission, the remaining Crit Ops are hidden to save space. Deselect the chosen mission to get them back.
* **Select your Tac Op**: The tracker allows you to choose you Tac Op from a pre-defined list, filtering them by archetype if you want to (Recon, Seek & Destroy, Security, Infiltration).
* **Primary Operation Selection**: Before "locking in", you must designate one of your selected Operations (**Kill Op**, **Crit Op**, or **Tac Op**) as your Primary Op. The tracker will then calculate a separate, adjusted VP total based on a 1.5x multiplier for points scored from your primary operation. This allows you to inform opponents of your "current score" without revealing your Primary Op choice.
* **Game Locking and Time Stamping**: Once you've made your selections, you can "Lock In" your choices and proceed to the tracking page. "Locking In" records the current date and time, which is then displayed at the bottom of the tracking page. This is to prevent undisclosed changes of your selections during the game. Players both using this tracker can lock in their choices simultaneously at the start of a match making the timestamps roughly identical.
* **Track Game Stats**: The tracker allows you to keep a running tally of the current **Turning Point (TP)**, as well as your current pool of **Command Points (CP)**, and your **Victory Points (VP)**. TP and CP must be adjusted manually but VP (and adjusted for the Primary Op) is calculated automatically. 
* **Kill Grade Table**: The app includes a dynamic table that shows the number of kills required to reach each of the Kill Grades, based on the number of starting enemy operatives you selected before Locking in.
 
### How It Works
The tracker is a self-contained HTML file. When opened, it presents you with a set of filters and card selections, followed by the tracker once your choices are finalised. By placing everything including the card data into a single file, it can then be easily hosted on Github or simply downloaded to your phone and/or PC and opened within your preferred browser.

### Notes from the Developer
This tracker was built primarily for my own personal use and is designed to be a simple tool for a common problem: clutter. While other, more fully-featured trackers are available, this one prioritises simplicity and being able to put all the tracking/game info into my pocket while moving around the table.
