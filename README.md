#"Capstone: Retrieving, Processing, and Visualizing Data with Python" -Coursera

The project is a part of "Capstone: Retrieving, Processing, and Visualizing Data with Python" offered on Coursera.

Installed SQLite browser to view and modify the database.
The link for the email archieve used is : http://mbox.dr-chuck.net/sakai.devel/

Overview in short is the following. For detailed explanation refer to README.txt.

1) gmane.py downloads emails from mbox.dr-chuck.net and stores it in a raw form in content.sqlite.

2) gmodel.py forms a relational database as index.sqlite from content.sqlite.

3) gbasic.py processes the email ids from index.sqlite to get the top email senders participants and top email organization from which they belonged.

4) gword.py processes subjects of email to get most frequent words and create visualization in gword.js using d3.js then gword.htm will have the word cloud representing the most used word in the subject with the largest font.

5) gyear.py/gline.py genrates tuples of (year,organization/domain) and pick top 10 organization and  the gline.js using d3.js library draws the line graph/histogram for each.


