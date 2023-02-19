![ic_scan_icon](https://user-images.githubusercontent.com/72518601/219952620-c5023639-b20f-43fa-885c-028df31f38dd.png)
![ic_scan_icon](https://user-images.githubusercontent.com/72518601/219952632-e04a7183-4ee9-4fd1-ad4b-64fd11a97481.png)


Create new drawable using this image
Name it 'scan_icon'


```xml
<fragment
        android:id="@+id/ScanPage"
        android:name="com.example.application.ScanPage"
        tools:layout="@layout/scan_page">

        <action
            android:id="@+id/action_Scan_to_List"
            app:destination="@id/[destination]" />
    </fragment>
```
Add to the navigation -> nav_graph xml file
