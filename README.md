# Can't update Excel links in Word (repro)

Please see my question on [superuser.com](https://superuser.com/questions/1755879/can-no-longer-update-excel-chart-links-in-word-except-with-a-weird-workaround)

Steps to reproduce:

1. Update the chart link in `Destination.docx` to reflect its actual path on your system (press Alt + F9 to view the link)
2. Edit the chart in `Source.xlsx`
3. Attempt to refresh the chart in `Destination.docx`

The link can be made to work again using the workaround described on superuser.com, but the same thing will happen whenever the Word file is closed and reopened.

Notes:

- I am seeing this behavior in Version 2210 Build 16.0.15726.20188
- I am not seeing this behavior in Version 2202 Build 16.0.14931.20648 (the links work here)
