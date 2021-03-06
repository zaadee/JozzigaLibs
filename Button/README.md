# Android Material Design Button Styles
With the Support Library v7, all the styles are actually already defined and ready to use, <br />
for the standard buttons, all of these styles are available:
<br /><br />
![button](https://cloud.githubusercontent.com/assets/10556500/22536841/c135beb4-e937-11e6-8908-bf13d2b29aa1.png)<br />
```xml
style="@style/Widget.AppCompat.Button"
```
![button colored](https://cloud.githubusercontent.com/assets/10556500/22536852/e274c00c-e937-11e6-8053-e8792522a88d.png)<br />
```xml
style="@style/Widget.AppCompat.Button.Colored"
```
![button borderless](https://cloud.githubusercontent.com/assets/10556500/22536851/e2466dec-e937-11e6-977e-5a9b64f9b8ee.png)<br />
```xml
style="@style/Widget.AppCompat.Button.Borderless"
```

![button borderless colored](https://cloud.githubusercontent.com/assets/10556500/22536850/e217adea-e937-11e6-905f-cb493738062c.png)<br />
```xml
style="@style/Widget.AppCompat.Button.Borderless.Colored"
```
<br /><br />

### Example!

```xml
<Button
    android:id="@+id/btn1"
    style="@style/Widget.AppCompat.Button.Colored"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="@string/button" />
```
### How to change color
Add custom style to styles.xml
```xml
<style name="AppTheme.Button" parent="Widget.AppCompat.Button.Colored">
    <item name="colorButtonNormal">@color/Red</item>
    <item name="android:textColor">@color/White</item>
</style>
```
Then add style to button.
```xml
<Button
    android:id="@+id/btn1"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="@string/button"
    android:theme="@style/AppTheme.Button" />
```
