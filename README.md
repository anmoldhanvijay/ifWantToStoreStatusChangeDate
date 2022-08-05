# ifWantToStoreStatusChangeDate
This is formula field which shows case status is closed date

IF( ISPICKVAL(statusPicklist__c, 'Completed' ) , ( LastModifiedDate ) , Null)
