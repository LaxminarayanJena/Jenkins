# Jenkins
java -Dhudson.model.DirectoryBrowserSupport.CSP="" -jar jenkins.war

java -jar jenkins.war

install latest jenkins.war and latest maven plugin


Jenkins used a cron expression, and the different fields are:

MINUTES Minutes in one hour (0-59) </br>
HOURS Hours in one day (0-23)</br>
DAYMONTH Day in a month (1-31)</br>
MONTH Month in a year (1-12)</br>
DAYWEEK Day of the week (0-7) where 0 and 7 are sunday</br>
If you want to schedule your build every 5 minutes, this will do the job : */5 * * * * </br>

If you want to schedule your build every day at 8h00, this will do the job : 0 8 * * * </br>

#### -------------------------------------------PROTRACTOR---------------------------------------------------
<img width="960" alt="Protractor1" src="https://user-images.githubusercontent.com/24494133/67222784-a802ef80-f44b-11e9-9e30-d6cfa764faeb.png">

<img width="961" alt="Protractor2" src="https://user-images.githubusercontent.com/24494133/67222801-ae916700-f44b-11e9-8ff0-4da49aaf6822.png">
