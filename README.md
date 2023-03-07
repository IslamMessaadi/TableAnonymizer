# TableAnonymizer
Servicenow Table data anonymizer simple tool helps you to anonymize/delete (calendar history) your data with full control. 

Supported algorithms:
+ MD5
+ SHA1
+ SHA256
+ Custom...

Supported Pattern options (You can configure your own regex / type pattern):
+ All (RegEx Based)

Use System Property (supported.Internal.field.type) to set you target field types.

# Important: 
In order to ADD/UPDATE/DELETE the history line data! You have to check canXXX option on table configuration level for these 3 tables:
+ sys_history_line
+ sys_audit
+ sys_journal_field

# ScreenShots:

![Table Anonymizer](https://user-images.githubusercontent.com/37014061/177036158-c3f75903-6492-4fcd-b982-619e270da063.JPG)

![form 01](https://user-images.githubusercontent.com/37014061/177010439-ff2b8ff6-8656-424d-bc72-9ab9eebb1b82.JPG)

![form 02](https://user-images.githubusercontent.com/37014061/177010443-ec1276ba-a010-427d-bc7f-88c9e3bf3e94.JPG)

Best regards,
