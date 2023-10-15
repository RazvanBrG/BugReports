# Bug Reports

Below are some Bug Reports that I discovered while working on previous projects.

--------------------

**Title:**
Loading time and resources

**Priority and severity:**
P2, High

**Description:**
The page loading time is too long and the resources are too big, so it is a performance problem.

**Steps to reproduce:**
1. Go to https://www.primariatechirghiol.ro/
2. Right click - Inspect
3. Go to "Network" tab
4. F5 and observe the resources size and loading time

**Expected result:**
The website should load faster.

**Actual result:**
The website is loading too slow.

----------------------

**Title:**
Text is too small

**Priority and severity:**
P2, High

**Description:**
The text is to small on other devices like phones.

**Steps to reproduce:**
1. Go to https://www.primariatechirghiol.ro/ from a smartphone and observe the text

   Or

1. Go to https://www.primariatechirghiol.ro/
2. Right click - Inspect
3. Press CTRL+Shift+M
4. Change the dimensions from "Dimensions" tab

**Expected result:**
The website text should be easier to read on phones.

**Actual result:**
The website text is not easy to read on phones because it is too small.

--------------------

**Title:**
Broken links

**Priority and severity:**
P1, High

**Description:**
The website has many broken links that will take the user to error pages.

**Steps to reproduce:**
1. Go to https://www.primariatechirghiol.ro/
2. Check some broken links like: https://www.primariatechirghiol.ro/formulare/arhitect-ef, http://www.fonduriadministratie.ro/, http://www.vilabellatechirghiol.ro/ (All the broken links can be found using online tools)

**Expected result:**
The website should have no broken links and all pages should be working well.

**Actual result:**
The website has many broken links that will take the user to error pages.

---------------------

**Title:**
Inappropriate values

**Priority and severity:**
P3, Normal

**Description:**
The user can type inappropriate values, like negative values, using “-” sign in any field and no error answer is given.

**Steps to reproduce:**
1. Go to https://www.globalsqa.com/angularJs-protractor/ConsumptionCalculator/
2. Type a negative value using “-” sign in any field

**Expected result:**
The website should not let the user type negative values or should return an error message.

**Actual result:**
The website let the user type negative values in fields and does not return any error message.

---------------------

**Title:**
404 Error

**Priority and severity:**
P3, Normal

**Description:**
The website 404 Error page is not customized and the user can not click any element, so he is blocked on that error page.

**Steps to reproduce:**
1. Go to https://www.demoblaze.com/index.html
2. Type any characters at the ending of URL

**Expected result:**
The website error page should let the user go to homepage.

**Actual result:**
The website error page doesn’t let the user to do anything and he is blocked there.
