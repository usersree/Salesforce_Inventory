# Salesforce_Inventory

### Instructions

+ To test the trigger, 
+ create an account.
+ Click Debug | Open Execute Anonymous Window.
+ In the new window, add the following and then click Execute.

'''
Vehicle__c v = new Vehicle__c();
v.Name = 'Sedan';
v.Last_Known_Odometer_Reading__c = 1001;
v.Last_Service_Date__c = Date.parse('12/20/2019');
insert v;
'''
