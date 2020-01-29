<!--LaRon Dashboard Framework. Author: Ronald Ngoda Email: ronniengoda@gmail.com Website: https://ronaldngoda.info Phone: +254708344101-->

# LaRon Appgini Dashboard Framework
>This is an appgini dashboard framework that uses adminLTE to easily generate an admin dashboard with nice looking cards for your appgini applications.You can easily customize the look and feel to suit your needs.Feel free to do whatever you want with it.Getting started is easy in two simple steps.
### New And Important Functions
## A List of most important functions you may need to use in your application dashbaord interface.
-LaRonCustomTableCard("Color","Icon","Name","Count","Link");<br>
-LaRonDataCard("color","name","icon","value");<br>
-LaRonDataCard2("color","name","icon","value");<br>
-LaRonBox("color","title","body");<br>
-LaRonAlert("color","icon","title","content");<br>
-LaRonCallout("color","title","content");<br>
-LaRonModal("color","modalID","btntext","title","body");<br>
-LaRonValues("query");<br>
-LaRonValue("query");<br>
-LaRonSQL("query");<br>
-LaRonBarChart($title,$subtitle,$data);<br>
-LaRonDonutChart($title,$chartHeight,$chartWidth,$data);<br>
-LaRonPieChart($title,$is3D,$chartHeight,$chartWidth,$data);<br>
-LaRonSplitButton($btnType,$btnText,$dropdownMenu);<br>
-LaRonSocialButton($text,$link,$type,$size);<br>
-LaRonAppButton($btnName,$link,$icon);<br>
-LaRonAppButtonBadge($btnName,$icon,$link,$counter,$color);<br>

>## Getting started
 1.Copy the laronlte.zip file into your appgini project directory and extract it in there.
 2.Once you have extracted go and run the installation file: install.php from your browser eg http://localhost/projectname/install.php
 3.This will install the LaRon dashboard framework on your appgini project and redirect you to your new dashboard.

## THATS SUPER EASY RIGHT??!!

Now lets see how you can customize the table cards colors and icons and even hide or display them based on users and groups.

# Customizing table cards colors and icons

> 1.Go to the helpers folder and find a file named tableCardsConfig.php
  2.In this file you will see all cases with your table names and the variables with the colors and icons.You can now change this to suit your project needs. And with that you are done with icons and colors.

# Hiding table cards or sidenav menu items based on groups and users.
> To hide or show cards or navmenu items, there is a code snippet commented in all the table cases wich you can uncomment and do your logic based on username,group or groupID.Below is a sample code

```php
if ($group=="Admins"||$group=="customers") {
			# code...
			$tablecard_visible="false";
			$sidenav_visible="false";
		}
```
In the above example you will be hiding the specific table card and sidenav menu for the Admins or customers group. When you set the value of visible to false the card or menu item will not be displayed.
You can now play around with this functionality untill you master it.I know you may be lost, but the best way to learn is to play with it untill you get sense LOL!!

Before i forget, there is one file called laron.php it is located in the helpers folder.You can always reffer to it as it contains more instruction and configuration variables and fucntions that display the cards and menu items.

### Thankyou very much for taking your precious time to read this. You can always come back here incase you missed a point.

```php
while($sense==null){
	comeREADME.md
}
```
