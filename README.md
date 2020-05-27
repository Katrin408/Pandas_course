Analysis of Udacity engagement data
Data description
Data is taken from Udacity course "Intro to Data Analysis": it's description of engagement of random subset of students who was taking Data Analyst Nanodegree.

Data files
Enrollments
Data about a random subset of Data Analyst Nanodegree students who complete their first project and a random subset of students who do not.

Columns:
account_key: A unique identifier for the account of the student who enrolled.
status: The enrollment status of the student at the time the data was collected. Possible values are 'canceled' and 'current'.
join_date: The date the student enrolled.
cancel_date: The date the student canceled, or blank if the student has not yet canceled.
days_to_cancel: The number of days between join_date and cancel_date, or blank if the student has not yet canceled.
is_udacity: True if the account is a Udacity test account, False otherwise.
is_canceled: True if the student had canceled this enrollment at the time the data was collected, False otherwise.
Daily engagement
Data about engagement within Data Analyst Nanodegree courses for each student in the enrollment table on each day they were enrolled. Includes a record even if there was no engagement that day. Includes engagement data from both the supporting courses for the Nanodegree program, and the corresponding freely available courses with the same content.

Columns:
acct: A unique identifier for the account of the student whose engagement data this is.
utc_date: The date for which the data was collected.
num_courses_visited: The total number of Data Analyst Nanodegree courses the student visited for at 2 minutes on this day. Nanodegree courses and freely available courses with the same content are counted separately.
total_minutes_visited: The total number of minutes the student spent taking Data Analyst Nanodegree courses on this day.
lessons_completed: The total number of lessons within Data Analyst Nanodegree courses on this day.
projects_completed: The total number of Data Analyst Nanodegree projects the student completed on this day.
