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
