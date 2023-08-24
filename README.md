# Overview

Replacing specific words to emojies on title of calendar events

```
#Work #Aborad XXX Conference     >>  🏢✈️ XXX Conference
#Parenting Gardening with child  >>  👶 Gardening with child
#Hospital Annual Health Checkup  >>  🏥 Annual Health Checkup
```

# Configure Google API

1) [Create Project](https://console.cloud.google.com/)
2) [Go to APIs & Services](https://console.cloud.google.com/apis/dashboard?project=myproject-396906)
3) [Enable Google Calendar API](https://console.cloud.google.com/apis/library/calendar-json.googleapis.com?project=myproject-396906)
4) [Create new OAuth2.0 Credential for Desktop App](https://console.cloud.google.com/apis/credentials?project=myproject-396906)
5) [Set OAuth consent screen](https://console.cloud.google.com/apis/credentials/consent/edit?project=myproject-396906) - Add scope (.../auth/calendar), and test user
6) [Download client_secret.json](https://console.cloud.google.com/apis/credentials?project=myproject-396906)

# Refer
https://developers.google.com/calendar/api/quickstart/python?hl=en