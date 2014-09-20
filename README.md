redmine_jobtime_update
======================

레드마인 작업시간 자동 업데이트 Tool

1. Rest API with C#

API Home Page: https://code.google.com/p/redmine-net-api/

File:      Redmine.Net.Api 0.11.zip   39.2 KB
Description:    
Fixed:
    Issue 61:    GetObject return relations.
    Issue 62:    Break compilatión on asp.net project.
    Issue 63:    GetObjectList don't get enumerations, error on path
    Parsing watchers from xml returned by redmine not working.
    Priority list is not returned.
    Change parent of an issue fails.
    Build fails in VB.NET
    IssuePriority/TimeEntryActivities json.
    (daqiang@qq17854.com) 

Features:

    Added spent hours to issue.
    Added closed_on to issue
    Added DownloadFile method.
    Added CustomFields(redmine api version 2.4 )

Patched:
    Get all users(daqiang@qq17854.com)