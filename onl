##  **TCS holiday booking script**

Login to ultimatix => Global ESS => Employee Perks => Holiday Homes => Apply

1. Choose the location you want to go, 
2. Select Room Type
3. Select the dates
4. Click I agree to terms and condition.

> These must be done atleast 2 min before 8am. (Dont do this too early, to prevent ultimatix session timout)

```javascript
Open console of the browser and paste this code. Not 100% guaranteed solution. 
System time must be exactly right and proper internet speed is expected.
Just give it a try.

var currentDate = new Date();
var triggerDateAndTime = new Date();
triggerDateAndTime.setHours(7);
triggerDateAndTime.setMinutes(59);
triggerDateAndTime.setSeconds(59);
triggerDateAndTime.setMilliseconds(900);
var milliSecondsRemaining = triggerDateAndTime.getTime() - currentDate.getTime();
setTimeout(tobeDone, milliSecondsRemaining);

function tobeDone() {
    document.getElementById('holidayHomesInitForm:book1').click();
}
```
