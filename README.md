### Test-cases ###

**Descriptions**

Attempt to log in with correct username and password.

**Steps to reproduce:**

1-Open emag.ro/login

2-Add correct user/pass

3-Click login button

**Expect result:**

User should be able to login and is redirected to his profile page.

**Test data:**

user : goeanadina@gmail.com

pass : 1234


**Pre-conditions**
User should have a valid account .

.......................................

**Descriptions:** 

Check if the login works when a user enters the wrong credentials.

**Steps to reproduce:**

1-Open emag.ro/login

2-Add wrong user and good pass

3-Click login button

**Expect result:**

User should not be able to login to his profile page. An error message should appear saying the user entered the wrong credentials and the forgot password link should be available.

**Test data:**

user : goean_adina@gmail.com

pass : 1234

..................................................

**Descriptions:**

Check if the search button works when a user try to do a search

**Steps to reproduce:**

1-Open emag.ro

2-Press search button and search "posca" word

3-Click search button or press the enter key

**Expect result:**

The list of all the markers that match the search for the suggested word should be visible to the user.

.............................................................................

**Descriptions:**

Perform a search for an item that does not exist on the website.

**Steps to reproduce:**

1-Go to laptop-direct.ro

2-Enter a non-existence item on the search bar (eg : pea)

3-Press the Enter key or click on the search button.

**Expected Result:**

The search should return zero results or an appropriate message indicating that no matching items were found.

eg : "Search for 'pea' returned 0 results. "

**Test data:**

user : goeanadina@gmail.com

pass : 1234

**Pre-conditions:**
User is on the homepage .

....................................................




