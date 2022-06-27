# Quiz-management-system
This is a quiz management system for teachers and students. In this database system some teachers can create question sets (quizzes) including multiple-choice questions and students can attempt questions sets 

the follow'ng assumtions and rules made to create the database


•	A question set (a quiz) is composed of at least 1 or many questions. We assume in this database; all questions are multiple choice questions.
•	A multiple-choice question can have at least 2 options or many more options
•	We assume only on option is correct
•	Each question is stored under category Course, Topic, and sub-topic. A question can be in several categories.
•	 Each question has question text, 2 or more options, 1 answer, feedback text, points.
•	Each teacher has name, teacherID, and email address.
•	Each student has name, studentID, program, and email address
•	Student can attempt a question set several times and the result of the attempt is stored. We are interested to see, what options were chosen by the student in every attempt and what the total point of that attempt is.
