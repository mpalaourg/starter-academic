---
title: Bash-ic shell
summary: Η υλοποίηση μου για το Bash Shell των Linux.
tags:
- bash
- terminal
- linux-unix
- C
date: "2016-04-27T00:00:00Z"

image:
  caption: ""
  focal_point: Smart

url_code: "https://github.com/mpalaourg/OperatingSystems_MyBash"
url_pdf: ""
url_slides: ""
url_video: ""
---

Ο στόχος είναι η υλοποίηση μιας απλουστευμένης εκδοχής του Unix shell στη C, όπου

- οι εντολές cd, help και quit αντιμετωπίζονται ως Built-In συναρτήσεις.
  - Για άλλες εντολές, πληκτρολογήστε ```@function_name @arguments```. Για περισσότερες πληροφορίες, πληκτρολογήστε ```man @function_name```.
- **Διαχείριση περιττών κενών**.
- **Ανακατεύθυνση μέσω >**.
- **Ανακατεύθυνση μέσω <**.
- Υποστήριξη δύο λειτουργιών:
  - **Διαδραστική**, όταν δε δίνεται όρισμα εισόδου.
  - **Μαζική εκτέλεση**, όταν δίνεται ένα όρισμα εισόδου (αρχείο).

Για μια πιο λεπτομερή περιγραφή της λειτουργίας, δείτε [εδώ](https://github.com/mpalaourg/OperatingSystems_MyBash#operating-systems-final-assignment-auth-2018).
