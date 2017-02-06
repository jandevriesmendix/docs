---
title: "XPath week-from-dateTime"
category: "refguide4"
space: "Reference Guide 4"
---
The week-from-dateTime() function extracts the amount of weeks from a DateTime attribute so it can be used to compare to a value. Values range from 1 to 53 (Which values belong to which week will depend on the database implementation)

<div class="alert alert-info">{% markdown %}

```
//Logging.Log[week-from-dateTime(DateAttribute) = 2]

```

This query returns all Logs where the amount of weeks in DateAttribute is 2, for example 2011-01-13\.

{% endmarkdown %}</div>