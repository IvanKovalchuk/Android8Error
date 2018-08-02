This aplication demonstrates an error in Android 8.0
The activity holds ViewPager. That ViewPager has 2 pages with one checkBox in them.
The second page's checkBox looks incorrectrly.

The issue appears when I change the checked state in onStart() or onResume() method.
If I set checkBox's state in  onCreateView(), checkBox looks fine.
[![The both CheckBox are checked](https://github.com/IvanKovalchuk/Android8Error/blob/master/device-2018-08-02-150257.png)]


