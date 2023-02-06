# `journal`

Highly hackable, and extremely fast, the basic premise for `journal` is a privacy preserving, future-proofed and searchable journal entirely powered by BASH. So, it just works and it practically always will.

## Install
```
curl \
-L https://raw.githubusercontent.com/alixanderthegreat/plain-text-bash-journal/main/journal \
-o /usr/local/bin/journal && sudo chmod +x /usr/local/bin/journal
```

## Menu

The `journal` app comes with a nifty menu. 

Be forewarned: `journal` uses `clear` everytime you make a choice. This is meant as a privacy feature much in the same way that you wouldn't leave a journal entry open, so `journal` clears the screen. 

```
$ journal

2023-02-05-20:31:16

Journal
1. Add
2. Review
3. Search
4. Backup
5. Analysis
6. Exit

Enter your choice:
```

### Add
Entries are added to the journal.txt in a `date,entry` fashion. Dates are in YYYY-mm-dd-HH:MM:SS format and each `entry` is added on the same line. This makes it really easy to sort and sort-merge with disparate editions of your `journal.txt`.

### Review 
Entries are in chronological order, which makes it really convenient to review the last... Say... 7 or 100 entries. It will lay out in chronological order. Like a journal would. 

### Search
This is, in my opinion, the coolest feature of a journal.txt. Wanna know something? Just search the keywords you want to look into and `journal`  will search for them in the text.

### Backup
This is a rudimentary backup system. Basically, each backup gets timestamped and is saved in the same folder as the journal.txt. 

### Analysis
Basic for the time being, but analysis can be done of the number of entries per month and word count. For now, that seems interesting.

