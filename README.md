# Alfred-workflow-get-weekday-of-date v2.0

# Note
One of my other workflows [`Find the weekday`](https://github.com/Stephen-Lon/Alfred-workflow-find-the-weekday) is, in my opinion, better than this workflow and does the same thing.

# Important note

In the configuration of this workflow you can choose to use European date format (dd/mm/yyyy) - which is the default - or, by un-checking the checkbox, choose to use the US date format (mm/dd/yyyy).

---

**For this workflow to work properly these must match:**

- the date format you choose in configuration of the workflow; and
- the format of your computer's short date in System Preferences > Language & Region > Advanced > Dates `Short:`.

**The workflow will not work properly if those settings do not match.**

---

# Usage

Type the keyword `wkday` followed by <space> and a date in the format you have selected in the configuration. The dialog will confirm the date and tell you the weekday of that date.

A regular expression checks for the correct input format.
