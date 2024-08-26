# Homework 1A: Create an Accessible PDF

## Deliverables

**Accessible PDF** - 25 points - due Tuesday, September 3, 11:59pm ET

## Getting Started

You will need to install a copy of Adobe Acrobat Pro DC on your own computer to do this assignment. Follow these instructions to get a free copy of Adobe Acrobat for use in this class.

**Adobe Creative Cloud Install Instructions**

1. Go to the Creative Cloud website (https://creativecloud.adobe.com) and click Sign In.
1. Sign in using the Sign-in Instructions below.
1. Click Install Creative Cloud App.
1. Double-click the installer file and follow the instructions.
1. Open the Adobe Creative Cloud application.
1. Sign in using the Sign-in Instructions below.
1. Once the application opens, click the Install button for each app that you want to install.
NOTE: If you have been provided with a license but cannot access the software after installing or are on a trial, log out of the Acrobat program and log back in using the Sign-in Instructions below to reset the Adobe License on your computer.

**Sign-in Instructions**

1. Enter your Andrew email address when prompted.
1. Click Continue and then, if prompted, click Company or School Account.
1. Enter your Andrew userID and password at the CMU Web Login screen.

The goal of this assignment is to create an accessible PDF from an inaccessible one. We will list instructions here, but they are pulled from a [larger document](https://chi2021.acm.org/for-authors/presenting/papers/guide-to-an-accessible-submission) helpfully put together for the CHI 2021 conference.

## Instructions

Download the [assignment file](Syllabus.pdf) and open using Adobe Acrobat Pro

### Check for Accessibility

1. Using the tools at the left side of the application find the **Prepare for Accessibility** Tool

1. Run the **Check for Accessibility** Tool. This tool will generate an accessibility report which you will turn in along with your accessibile PDF document (Make note of where this report is saved so you can find it later). In Acrobat this should open up a pane on the right side showing several issues with the current document including:
	1. Document Issues
		- Tagged PDF
		- Logical Reading Order
		- Primary Language
		- Color Contrast
	1. Page Content
		- Document Tags
		- Tab Order
	1. Alternate Text
		- Figures have no Alternative Text
	1. Tables
		- Table Content not properly tagged
		- Rows
		- TH and TD
		- Headers
		- Regularity
	1. Lists
		- Not Properly Tagged
	1. Headings
		- Not Properly Nested

### Fix Accessibility Issues
	
1. **Add Accessibility Tags** to the document
	1. Using the Prepare for Accessibilty Tool > Automatically tag PDF

1. **Fix Tab Order**
	1. Open Thumbnail View for the PDF pages using the toolbar on the right
	1. Select all pages
	1. Right Click and select *page properties*
	1. Select *Use Document Structure*

1. Update the metadata by going to *File > Document Properties*
	1. **Set Author Name**: 
		On the Description tab set the author name to "YOUR NAME - Andrew ID"
	1. **Set Primary Language**: 
		On the Advanced tab, under Reading Options set the langauge.

1. Check for **Logical Reading Order**
	1. Under the *Prepare for Accessibility tool*, Open the *Fix Reading Order* panel.
	1. The document should now show highlighted and numbered sections. These sections should be properly separated and numbered according to the logical order they should be read on the page.
		NOTE: Make sure the *Page Content Groups > Page Content Order* Options are selected.

1. **Fix Improperly Tagged Elements** using the Reading Order tool
	1. Highlight the content you want to tag then click the proper tag using the reading order tool. You can use this [guidance on using the tool](https://helpx.adobe.com/acrobat/using/touch-reading-order-tool-pdfs.html) if you get stuck. Be sure to pay attention to:
	  1. Headings vs Content
	  1. Tables vs Figures

1. **Add Alternative Text** for Figures
	1. Using the *Prepare for Accessibility Tool* (Left Side), click *Add alternate text*
	1. Add text descriptions for each instructor and teaching assistant image.

1. Run the **Check for Accessibility** tool again to make sure you've addressed all issues.

1. **Save the PDF** again, close it, and reopen it to double-check that your accessibility features have been saved.
2. Turn in the **Final PDF** .



## Submission

Submit the final PDF to Gradescope.
