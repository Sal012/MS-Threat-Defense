<p> <i> The SecurityEvents table contains security events collected from windows machine can be reported by Security Center or Microsoft Sentinel.</i> </p>

*The table name is case sensitive.*

To see the list of all the security events reported to log analytics, you can run the following query:
<p> 
  Security Events
</p>

**Note:** This will retrun all the security events present in the database, which will strain the database a lot. It's therefore a good practice to filter the query based on the time duration for which you need analyse the data for. 

For example, if you want to see all the security events that were reported to log analytics in last 24 hours, you can use following query:

<p> 
 SecurityEvent
| where TimeGenerated > ago(1d)
</p>
