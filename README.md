# codespace-2k19-timer

Timer for the hack which i created to be showcased during the last few hours of hackathon coding period.

![Codespace Timer](/Codespace-2k19-cover-social_preview.png "Social Preview")


:octocat: This website is hosted as [codespace-2k19-timer](https://pranshupranjal.github.io/codespace-2k19-timer/)

---

The two variables deciding the time start and end are startTime and endTime.

startTime = `Date.now();`

endTime = `Date.now() + 86400000;`;

Currently for showcasing purposes endTime is stated as 24 hours from the current time as the page opens.

_Also, the timer will reset if the page is refreshed._

---

### Note:

`endTime = Date.parse("31 Mar 2019 16:00:00")`

is an example of how to store the endtime variable.

_By this method, the timer won't reset even if the page is refreshed._