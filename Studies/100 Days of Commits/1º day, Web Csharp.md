First, identify the problem. The new user is being saved, with the correct ID, Username, and Password. Creating a new user is not working. The old information seems to be getting replaced by the new one. The ID is not changing, which it should, as there is a function that makes the ID get +1 if it isn't the first one. 

Possible problems, and possible solutions:

1. The list isn't working, and it is only showing the newest item in the list.
- This cannot be true, as the ID is not changing, unless the ID changing function is broken by itself. (Found out that the ID in general is not working. Ffs.)
- Should see if the list function is receiving the full list. If not, find out why it isn't.

2. The other problem, it isn't saving correctly the new user. The ID is being saved incorrectly, as already proven, and the new user is overwriting the old one.


Tried fixing the ID. Didn't work. 