Writes a message to the event log.
==================================

            

 


 

 

 

 This runbook is responsible for writing log entries into event log. This is quite a common requirment and there are specific steps that needs to be performed for writing to event log. THe Event log should exists. THe event
 source should also exists. This runbook does not create new event logs but if the event source is not present, it would create it. After creating the event source, it would log the log message to the event log. If the event source already exists, this runbook
 will write to the same source directly.


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
