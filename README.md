# Circle countdown

JavaScript countdown clock library.

This project is deployed on GitHub Pages.

## Sample

* http://jcombes.github.io/countdown-circle/?date=2020-01-18T12:00:00Z

* http://jcombes.github.io/countdown-circle/?date=2020-01-18T12:00:00Z&days-color=#EFE532&hours-color=#EFE532&minutes-color=#EFE532&seconds-color=#EFE532&circle-bkcolor=#24463E

* http://jcombes.github.io/countdown-circle/?date=2020-01-18T12:00:00Z&days-color=#EFE532&hours-color=#EFE532&minutes-color=#EFE532&seconds-color=#EFE532&circle-bkcolor=#24463E&days-text=Jours&hours-text=Heures&minutes-text=Minutes&seconds-text=Secondes


## Parameters

Parameter | Default | Description
------------ | ------------- | -------------
date |  | String representing a date (<a href="http://tools.ietf.org/html/rfc2822#section-3.3" target="_blank">RFC2822 - Section 3.3</a> or ISO 8601). I recommand to use the format `YYYY-MM-DDTHH:MM:SSZ` which is compatible with all browsers.
end-text | | The text displayed when the countdown is finished.
days-show | 1 | If 1, the circle representing the days is displayed.
hours-show | 1 | If 1, the circle representing the hours is displayed.
minutes-show | 1 | If 1, the circle representing the minutes is displayed.
seconds-show | 1 | If 1, the circle representing the seconds is displayed.
days-color | #FFCC66 | Color of the circle representing the days.
hours-color | #99CCFF | Color of the circle representing the hours.
minutes-color | #BBFFBB | Color of the circle representing the minutes.
seconds-color | #FF9999 | Color of the circle representing the seconds.
days-text | Days | Text indicating the number of days.
hours-text | Hours | Text indicating the number of hours.
minutes-text | Minutes | Text indicating the number of minutes.
seconds-text | Seconds | Text indicating the number of seconds.
circle-bkcolor | #60686F | Background color of the circle.
