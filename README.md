# Daily-work (14-11-22)
Today my task was to complete the requirements of CMC Project.The requirements  that we have to fullfile are:

1) If sales invoice value exceeds estimated cost then give alert message.

2) if sales invoice value exceeds Sanctioned cost then shouldn't
generate the bill.

- Inorder to complete we think that these requirements may be completed by the
  Notification feature in frappe. Me and pranvir just check it and we
  see that we can apply the condition in the "Condition" field. But this does not work for us.
-  Then we find one more solution that, there is a feature in client script called frappe.msgprint(). This function can be used with some conditions, so we can apply our conditions here.
-  Firstly we follow this link https://discuss.erpnext.com/t/client-script-to-fetch-value-from-another-doctype/1095/3 tutorial, to get alert message in sales invoice. In this tutorial we use one script and we test it on **gne12.gndec.ac.in**.

# Daily-Work (15-11-22)
Before start work things that i learn are :
## 1) Connection in doctype:
Inorder to make connection we have to link two
Stock work 12:00 -

# Daily-Work (17-11-22)

- In the morning, I learn from my team member that how we can apply condition  in the doctype ,like we have to do one task that get the alert message when total bill(sales invoice) is greater then the estimate cost. 
- I do discussion with team about student data or informtion because we have to add the hosteler(student) in the CMC project.So just create 5,6 student then enroll them in their respective program(CSE,MBA etc) and course(subject).This work com eunder the Education Domain in the erp.
- In the afternoon there was a meeting with teachers(Mentors) about our task and guidlines.In the meting we put our points and did the discussion about the project.
- Now my task was to upload the user(employee)on erp.So this work is done through Data import list ,where i  download the template according to requirment and put the provided data in the downloaded template and save it with .csv extenstion.There was  many  problem faced by me while uploading the user which are:
1) In the first time it showing the error that **The following values do not exist for Department: Computer Science Engineering ??? GNDEC**
2) Error regarding the User id of user(employee) which was their e-mail.

# Daily-Work (18-11-22)

- Today at morning 8:30 uploading the left user on erp.gndec.ac.in
- 9:00 Disscuss the CMC project with team.
- 10:25 Disscuss the Nankana Project with Satinder sir and had a meeting with Nankana School officals at 11:15.
- 11:15-12:26 In the meeeting we show our work to them and get their views on it and their requirements.
- 12:38 Discuss a problem related to the guru.gndec.ac.in with Amarpreet Mam(MBA Block).
  
  Working on rest of work.
  
# Daily-Work (19-11-22)
  
 - Today we went to the Nankana School and had the meeting with teachers .In the meeting they show us their feebank software and school fee structure.
 - In the evening their was seminer of other GD members .

# Daily-Work (21-11-22)

- Start working on Nankana Public school project and trying to meet their requirements in student applicant form.
- 10:32 -  The first thing they want in sibling  details  table is that
they only want to select the student ID and other details of selected
student come accordingly.This  work is done , now we only have to select the
student id and corresponding to this  First ,last name ,gender and
date of birth is come accordingly.
- Set the stock problem in erp.gndec.ac.in ,like disable the unwanted item .
- Trying to solve the error in quotion , like it was give the error of multicurrency _ invoice while creating the sales invoice.

# Daily-Work (22-11-22)

- Working on Education domain like Student Admission ,Fees.
- Did some work on guru.gndec.ac.in, solved the problems faced by teacher regarding participents in the courses.
  
# Daily-Work (23-11-22)

- Today i make connection of fee on student applicant form.
- Work on Fees Structure and make some program and fee category.

# Daily-Work (24-11-22)

- Make some LDAP user then upload and enroll them in their respective courses.
- Make duplicate of student applicant form to do same changes without changing the core of form.
- Make refrence workflow to understand the process and discuss it with Komal.

# Daily-Work (25-11-22)

- Today , I work on Nanak School project :

 1. Create the doctype Applicant Form ,add the connection of Applicant
fee in the doctype.

 2. Did some work on a CMC project like Company address and learned one
thing that we can we a customer an internal customer under
representing company from @ Rai sir.

 3. Create one more doctype Registration Form and also add the
connection  form where Applicants who submit the applicant fee can
submit his/her registration fee (5000).
Things now i am going to do is that in the registration fee form ,fee component fetch automatically while selecting the fee structure.

# Daily-Work (26-11-22)

- Today ,I am going to set the  view of the dashboard for the accountantmam(Nankana School Teacher). After this i will work on fee structure and fee         concession according to the school.

# Daily-Work (28-11-22)

- This morning all SDC members had a meeting  (google meet) with Satinder Sir regarding work progress . So in the meeting we discussed our problem  and    work status with sir.In our task (School project), sir told us to make workflow for applicant and registration forms instead of making different doctype
for each stage. Set permissions under it until the applicant did not deposit 500/- could not be able to open the registration form. Similarly if    registration has been completed only then he/she is able to see the enrollments.
So, now we(Jasjit, Komalpreet) are working on it .

# Daily-Work (29-11-22)

- Today we had a discussion with @ Satinderpal Sir and sir told us that we have to do all the steps (applicant and registration fee )  in one
doctype.For this we have to make three connections (Applicant fee , Advance Fee or Registration fee , Admission fee) in one doctype so it will be easy for us to do all the steps accordingly.
- I made one doctype named Student Form in gne12 and added the three connections of fees which are shown after saving the form. These fees are Applicant Fee , Advanced Fee and Fee.
# Daily-Work (30-11-22)

- Today my task is to add an Action button of Approved , Reject and
Enroll button on student applicant doctype so that after submitting
the fees and applicant form we enroll the applicant in a program or
course.

# Daily-Work (1-12-22)

- ??Last we discuss the Student Applicant process with @ Satinderpal Sir and sir said us to make the connection of fees on one doctype so accordingly to sir we create one doctype named Waheguru on gne2.gndec.ac.in under Education Domain . In this doctype we (me, Komalpreet) make the connection of Applicant fee, Advanced Fee.After saving the form these connections are visible  and then we submit the form.
Then the task was to add an action button on this, this action button was about Approved or reject the form and after applying the condition of approved or reject we update the form the enroll option to enroll the applicant in the Program.

- Now the problem we faced was that when we enroll the applicant by clicking on Enroll button on Waheguru doctype it shows that:
"Student Applicant NSPS-SESSION-2023-2024-00003 not found" So, we are going to resolve the conflict.
- I think that it is because there is no relation between Waheguru and Program Enrollment doctypes , so now I am going to see it and report here regularly if it work.

 # Daily-Work (2-12-22)
 
 - Today we crete the user for NSPS school. These user are the Teachers ,so give them Instructor role at last. The main motive was  to show the courses to the instructor. For this we have to create the program ,courses. 
 
