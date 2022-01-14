**What the community is struggling with**

According to the survey that Microsoft carried out, people who are at the beginning stage off KQL usually struggle with the fact that they know the commands and they know the keywords to some extent but they do not know how to apply those commands and those keywords in the context that they understand the languages applicability. secondly most of the people find the available resources around learning KQL to be focused on what keywords are available, but not necessarily how to tweak or use them in the context in the most efficient way.

Some people have also mentioned that they struggle to find KQL learning material that is focused on using Microsoft Sentinel and building use cases around it. These challenges I  struggled with as well, which I am attempting to make it easier for the community.

**Let's start with the basics of KQL**

KQL stands for Kusto Query Language, and this is used in a lot of Microsoft products like MS defender, log analytics, Microsoft Sentinel and so on. If you are into Microsoft and specially in security domain, KQL is something that you just cannot ignore. if you are going to write queries to see what happened, or you want to write custom reports for management, or make nice analytics presenting information in the form of graphs, pie charts, bars charts etc, KQL is something that you cannot do without. it's a very important language to have in your arsenal.

**How KQL works:**


Let's consider the example of log analytics in Microsoft Azure. Log analytics is another name for the database which resides in the cloud, which you can query and get the results from. Based on which connectors you configure, and what data sources you connect to your log analytics workspace, different sets of tables in this database get populated. For example, security events that get reported to MS Sentinel, get populated in SecurityEvent table. DNS logs/ events get populated in the table called DnsEvents. threat intelligence feed gets populated in the table called ThreatInte demolligenceIndicator.
This is safe the database is built around a model where you pay for what you use, so if you buy for shorter amounts of time or inject comparatively less data to Log Analytics database, you will pay less. However, if you if you want to keep more data or for longer periods of time, you will have to pay more.
Other services like Microsoft Sentinel, or defender for Endpoint, defender for Microsoft Office 365 etc also use KQL. part of the reason is that these services also have to ingest their data into log analytics tables. these tables can we work on, to make our analysis, and find out what is going on end our network.

**AKA.MS/LADemo:**


To have a look and feel of how this database looks like, which tables are there to play around with, I recommend going to the website aka.ms/lademo. If this is the first time you are connecting to it, you might need to create a Microsoft account to get access. this is a demo environment - hence the name LADemo (Log Analytics Demo). this database is pre populated by Microsoft and contains data for us to query and play around with.



