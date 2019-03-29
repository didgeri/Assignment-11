# Ging-Final-Project
Ging assignment 11 for Berklee programming 101.  Pulls two api's and creates a list combining them.

Known issues:
*if you search for an artist that doesn't have any upcoming events there will be no return, but also no noticeable way
  to see that your query was returned, aside from the "submit" button going back to grey, from the "still working" blue.
  The totalReturn var will also say your query returned "0" total events.
*Not necessarily an issue, but a matter of preference:  The search results stack on top of previous search results until
  you decide to hit the "clear" button.
*Any search query with intended spaces needs to have dashes instead of spaces.  (The Devil Wears Prada, needs
  to be: "the-devil-wears-prada")
*Date formatting between the two different API's is very different, and requires further code to be able to compare
  them correctly.
