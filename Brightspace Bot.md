- Get events from Algonquin College Brightspace iCal feed.
- Parse them to get:
	- Course Number
	- Course Name
	- Assignment Name
	- Deadline
	- Weight (1%, 6%, etc.)
		- Will require matching with Grade list in Brightspace, can use custom Brightspace API, or manually print each grade page and parse, or manually assign weights to tasks using regex.
- Could download files from assignment and use AI to summarize.
- Could automatically download slides and convert to PDF, add them to Obsidian vault.

Brightspace OAuth 2.0

## acbrightspace
- Python library that works with Algonquin College's Brightspace
- Get grades
- Get assignments
- Get courses
- Get content


