This application demonstrates an error in Android 8.0
The activity holds a CheckBox and a ViewPager. That ViewPager has 2 pages with one CheckBox in each.
The second page's CheckBox looks incorrectly.

The issue appears when I change the checked state in onStart() or onResume() method.
If I set CheckBox's state in  onCreateView(), the CheckBox looks fine.

![The both CheckBoxes are checked](https://github.com/IvanKovalchuk/Android8Error/blob/master/device-2018-08-02-150257.png)


