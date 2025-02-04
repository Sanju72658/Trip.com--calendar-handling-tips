Production page validation of Trip.com
1.Validate trip.com is loaded successfully
2.validate a departure airport can be successfully selected from a dynamic list of cities
3.validate a destination airport can be successfully selected from a dynamic list of cities
4.validate successfull selection of desired dates for two way travel 

The script validates successfull selection of dates from default month and year. For other dates, the script navigates to desired date and selects successfully.
Fixed Code > Consecutive months are shown while opening calendar. The script caused issues while validating dates of consecutive months as navigation is not required for return date. The script is modified such that, check for consecutive months before navigating. If the travel dates are on the consecutive months, then do not navigate, else navigate for return date selection.
