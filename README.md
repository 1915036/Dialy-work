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
1) In the first time it showing the error that **The following values do not exist for Department: Computer Science Engineering – GNDEC**
2) Error regarding the User id of user(employee) which was their e-mail.
