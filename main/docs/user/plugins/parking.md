---
sidebar_position: 4
title:  Parking position
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';
import AndroidStore from '@site/src/components/buttons/AndroidStore.mdx';
import AppleStore from '@site/src/components/buttons/AppleStore.mdx';
import LinksTelegram from '@site/src/components/_linksTelegram.mdx';
import LinksSocial from '@site/src/components/_linksSocialNetworks.mdx';
import Translate from '@site/src/components/Translate.js';
import InfoIncompleteArticle from '@site/src/components/_infoIncompleteArticle.mdx';

<InfoIncompleteArticle/>

Setting a point on the map of where your car is left in the street, and a calendar notice of when the parking time started to count down, will comfort your efforts in keeping track of the time and the car location.

## Overview 

A Parking point on the map and a notice in the calendar are provided by the Parking plugin. It is free, and works well with the downloaded OsmAnd Maps and Navigation. A Parking point will help you remember the exact location of where the car is left as well as to stay aware of how far it is already from your parking spot, and if needed, to return on time, avoid additional unnecessary costs, share the location with your loved ones. It is easy to set a Parking point, with or without time-tracking, and to remove it after successful use. 


<Tabs groupId="operating-systems">

<TabItem value="def" label="Default" default>

![Parking widget iOS](@site/static/img/plugins/parking/parking_widget_ios.png) ![Parking widget Android](@site/static/img/plugins/parking/parking_widget_android.png)  

</TabItem>

<TabItem value="ios" label="iOS">

![Parking widget iOS](@site/static/img/plugins/parking/parking_widget_ios.png)

</TabItem>

<TabItem value="android" label="Android">

![Parking widget Android](@site/static/img/plugins/parking/parking_widget_android.png) 

</TabItem>

</Tabs>


&nbsp;&nbsp;&nbsp;&nbsp;

## Setup

For using a Parking point on the map, the following setup is required:

1. Enable the plugin.

2. Make certain the Parking widget is added to the screen. 

### Enable plugin

<Tabs groupId="operating-systems">
<TabItem value="def" label="Default" default>

The [Parking widget](../widgets/info-widgets.md#-parking-widget) becomes available with the Parking plugin enabled. In the list of the plugins, find the Parking one and enable it. 

![Parking plugin in Android](@site/static/img/plugins/parking/parking_plugin_android.png) ![Parking plugin in iOS](@site/static/img/plugins/parking/parking_plugin_ios.png)

</TabItem>

<TabItem value="ios" label="iOS">

In the **iOS** version, to enable the Parking plugin, open the list of plugins, find the Parking one, check it and confirm with the **Ok** button in the next dialog. 

**<Translate ios="true" ids="ios_button_seq"/>:** <Translate ios="true" ids="menu,plugins,product_title_parking"/>

![Plugin confirmation in iOS](@site/static/img/plugins/parking/ios_add_parking_plugin.png)

</TabItem>

<TabItem value="android" label="Android">

In the **Android** version, to enable the Parking plugin, tap the triple dots at the right side of the <Translate android="true" ids="osmand_parking_plugin_name"/>  option, then tap **Enable**, and confirm with the **OK** button in the next dialog.

**<Translate android="true" ids="android_button_seq"/>:** <Translate android="true" ids="shared_string_menu,plugins_menu_group,osmand_parking_plugin_name"/> 

![Plugin confirmation in Android](@site/static/img/plugins/parking/and_add_parking_plugin.png)

</TabItem>

</Tabs>


&nbsp;&nbsp;&nbsp;&nbsp;


### Add Parking widget

<Tabs groupId="operating-systems">

<TabItem value="def" label="Default" default>

The [Parking widget](../widgets/info-widgets.md#-parking-widget) is added automatically to the screen once the Parking plugin is enabled. However, before setting a Parking point, make certain you have the plugin on the screen, and if not, add it by enabling the respective option in the [Configure Screen](../widgets/configure-screen.md) menu. The Parking widget will help you quickly reach out to the Parking point on the map. 

![Adding Parking widget in iOS](@site/static/img/plugins/parking/ios_adding_parking_widget.png) ![Adding Parking widget in Android](@site/static/img/plugins/parking/and_adding_parking_widget.png)

</TabItem>

<TabItem value="ios" label="iOS">

In the **iOS** version, toggle on the <Translate ios="true" ids="product_title_parking"/> widget in: 

**<Translate ios="true" ids="ios_button_seq"/>:** <Translate ios="true" ids="menu,layer_map_appearance,product_title_parking"/>


![Adding Parking widget in iOS](@site/static/img/plugins/parking/ios_adding_parking_widget.png)

</TabItem>

<TabItem value="android" label="Android">

In the **Android** version, toggle on the <Translate android="true" ids="map_widget_parking"/> widget in: 

**<Translate android="true" ids="android_button_seq"/>:** <Translate android="true" ids="shared_string_menu,layer_map_appearance,map_widget_parking"/> 

![Adding Parking widget in Android](@site/static/img/plugins/parking/and_adding_parking_widget.png)

</TabItem>

</Tabs>


&nbsp;&nbsp;&nbsp;&nbsp;

## Parking point on the map

When a Parking point shows up on the map, it acquires the latitude and longitude of the selected geolocation, and the timestamp of the creation moment. It helps visually to identify the parking both when setting the point and when further tracking it as well as using for navigation, if necessary. There are a number of ways of how to store the parking information and use it for checking out the time, and/or location. 


###  Set a point

<Tabs groupId="operating-systems">

<TabItem value="def" label="Default" default>

To set a Parking point on the map, zoom in to the required level, then long-tap a spot on the map, and in the opened [Context menu](../map/map-context-menu.md), do the following: 

1. Tap [**Actions**](../map/map-context-menu.md#-add--delete-parking-point).
2. Tap **Parking**.
3. If needed, set time, and add a reminder to the Calendar app. 
4. **Save** the point. 

![Set Parking point in iOS](@site/static/img/plugins/parking/ios_set_p_point_limit.png) ![Set Parking point in Android](@site/static/img/plugins/parking/and_set_p_point_limit.png) 

</TabItem>

<TabItem value="ios" label="iOS">

In the **iOS** version, to set a Parking point, long-tap a spot on the map and in the opened [Context menu](../map/map-context-menu.md), do the following:

1. Tap **<Translate ios="true" ids="actions"/>**, and then tap **<Translate ios="true" ids="add_parking_short"/>**.
2. Consider time limits in the opened <Translate ios="true" ids="parking_marker"/> dialog. If a time limit is needed, enable the **<Translate ios="true" ids="time_limited"/>** option, and establish the following:

    - time when to end parking;
    - reminder for the Calendar app.

3. Tap **Save**, and the point will be set on the map. 

![Select Parking in Actions in iOS](@site/static/img/plugins/parking/ios_set_p_point2.png)  ![Set Parking point in iOS](@site/static/img/plugins/parking/ios_set_p_point3_.png)

</TabItem>

<TabItem value="android" label="Android">

In the **Android** version, to set a Parking point, long-tap a spot on the map and in the opened [Context menu](../map/map-context-menu.md), do the following:

1. Tap **<Translate android="true" ids="shared_string_actions"/>**, and then tap **<Translate android="true" ids="context_menu_item_add_parking_point"/>**.
2. Consider time limits in the opened <Translate android="true" ids="parking_options"/> dialog: 

    - If there is no time limit, select the **<Translate android="true" ids="osmand_parking_no_lim_text"/>** option, and the point without time constraints will be set on the map. 

    - If a time limit is required, select the **<Translate android="true" ids="osmand_parking_time_limit"/>** option, and then: 
        - select time when to end parking;
        - add reminder for the Calendar app;
        - tap **OK**, and the point with the established time limit will be set on the map. .

![Set Parking point in Android](@site/static/img/plugins/parking/and_set_p_point_limit.png) ![Set time limits in Android](@site/static/img/plugins/parking/and_set_p_point4_.png)

</TabItem>

</Tabs>

>**NOTE**: The start time is always established automatically for the Parking point. The end time, if selected to be set for the Parking point, can be re-added anew only, not edited. The expected end time of the parking reminder in the Calendar app can be updated as needed. 


&nbsp;&nbsp;&nbsp;&nbsp;

### Stay informed

<Tabs groupId="operating-systems">

<TabItem value="def" label="Default" default>

To stay aware of the parking location and the time, after a Parking point is set, you can use: the [Parking widget](../widgets/info-widgets.md#-parking-widget) and the context menu of the point on the map. 

#### LOCATION

**Location** is revealed by the [Parking widget](../widgets/info-widgets.md#-parking-widget). It helps to see the distance from your current location, or the center of the screen to the Parking point. Additionally, by tapping the widget the map immediately brings the Parking point into the center of your screen. 

![Parking widget iOS](@site/static/img/plugins/parking/parking_widget_ios.png) ![Parking widget Android](@site/static/img/plugins/parking/parking_widget_android.png) 


#### START TIME

**Start Time** is always visible in the details of the Parking point. To see the details, tap the Parking point, and the opened context menu will show you when Parking started. 

![Parking info in iOS](@site/static/img/plugins/parking/ios_parking_info.png) ![Parking info in Android](@site/static/img/plugins/parking/and_parking_info.png)


#### TIME LEFT / OVERDUE

**Time Left** or **Time Overdue** is provided in the details of a time-limited Parking point to show an initial expectation of when the car was planned to be picked up. To see the time left or overdue, tap the time-limited Parking point, and the opened context menu will show you when Parking was expected to be ended. 

![Time left in iOS](@site/static/img/plugins/parking/ios_parking_info_left.png) ![Time left in Android](@site/static/img/plugins/parking/and_parking_info_left.png) 


#### CALENDAR REMINDER

**Calendar reminder** is helpful in keeping track of the time by highlighting the end of Parking. To add a reminder about the end of Parking time to your Calendar app, select the respective option when setting a time-limited Parking point. 

![Parking reminder in Calendar](@site/static/img/plugins/parking/ios_parking_in_calendar.png)

</TabItem>

<TabItem value="ios" label="iOS">

**Location** is revealed by the [Parking widget](../widgets/info-widgets.md#-parking-widget). Whenever the app is closed, and re-opened again, the Parking widget will help you find the Parking point on the map. It is enough to tap the widget, and the map will show the Parking point. 

Also, the widget shows the distance from your current location, or the center of the screen to the Parking point.

![Parking widget iOS](@site/static/img/plugins/parking/parking_widget_ios.png)

**Start Time** is always visible in the details of the Parking point. To see the details, tap the Parking point, and the opened <Translate ios="true" ids="parking_marker"/> context menu will show you when Parking started. 

![Parking info in iOS](@site/static/img/plugins/parking/ios_parking_info.png) 


**Time Left** or **Time Overdue** in the details of a time-limited Parking point, opened with the <Translate ios="true" ids="parking_marker"/> context menu, will show the overall amount of time: either left up to the expected end of the parking, or overdue since then. 

![Time left in iOS](@site/static/img/plugins/parking/ios_parking_info_left.png)

**<Translate ios="true" ids="add_notification_calendar"/>** is the option that if enabled during setting a time-limited Parking point, creates a reminder about the end of Parking time in the default Calendar app on your device. 

![Parking reminder in Calendar](@site/static/img/plugins/parking/ios_parking_in_calendar.png) 

</TabItem>

<TabItem value="android" label="Android">

**Location** is revealed by the [Parking widget](../widgets/info-widgets.md#-parking-widget). Whenever the app is closed, and re-opened again, the Parking widget will help you find the Parking point on the map. It is enough to tap the widget, and the map will show the Parking point.

Also, the widget shows the distance from your current location, or the center of the screen to the Parking point.

![Parking widget Android](@site/static/img/plugins/parking/parking_widget_android.png)

**Start Time** is always visible in the details of the Parking point. To see the details, tap the Parking point, and the opened <Translate android="true" ids="parking_place"/> context menu will show you when Parking started. 

![Parking info in Android](@site/static/img/plugins/parking/and_parking_info.png) 

**Time Left** or **Time Overdue** in the details of a time-limited Parking point, opened with the <Translate android="true" ids="pick_up_till"/> context menu, will show the overall amount of time: either left up to the expected end of the parking, or overdue since then. 

![Time left in Android](@site/static/img/plugins/parking/and_parking_info_left.png) 

**<Translate android="true" ids="osmand_parking_add_event"/>** option, if checked in the **<Translate android="true" ids="osmand_parking_time_limit_title"/>** popup during setting a time-limited Parking point, creates a reminder about the end of Parking time in the default Calendar app on your device. 

</TabItem>

</Tabs>


&nbsp;&nbsp;&nbsp;&nbsp;

### Navigate to the point

<Tabs groupId="operating-systems">

<TabItem value="def" label="Default" default>

A Parking point can be used for navigation, if the geolocation is unknown, and/or simply to find an optimal course when heading to where the car is parked. To provision the Parking point to the navigation functionality, do the following:

1. Tap the navigation icon on your map. 
2. Select the profile. 
2. Tap the From field, and select an option of your current position.  
3. Tap the To fiels, and select the Parking option. 

![Heading to Parking point in iOS](@site/static/img/plugins/parking/ios_going_to_parking.png) ![Heading to Parking point in Android](@site/static/img/plugins/parking/and_navigating_to_parking.png)

</TabItem>

<TabItem value="ios" label="iOS">

To show the route from your current position to the Parking point, tap the navigation icon on the map, select the profile (i.e. on foot, public transport, etc.), and then tap the **To** field and among the available options look for **<Translate ios="true" ids="parking"/>**.

![Heading to Parking point in iOS](@site/static/img/plugins/parking/ios_going_to_parking.png)

</TabItem>

<TabItem value="android" label="Android">

To show the route from your current position to the Parking point, tap the navigation icon on the map, select the profile (i.e. on foot, public transport, etc.), and then tap the **To** field and among the available options look for **<Translate android="true" ids="osmand_parking_position_name"/>**.

![Heading to Parking point in Android](@site/static/img/plugins/parking/and_navigating_to_parking.png)

</TabItem>

</Tabs>


&nbsp;&nbsp;&nbsp;&nbsp;

### Remove the point

<Tabs groupId="operating-systems">

<TabItem value="def" label="Default" default>

Once the Parking point is not needed anymore, remove it by long-tapping the point and selecting the respective option in the opened [context menu](../map/map-context-menu.md#-add--delete-parking-point). If any reminder, it will be deleted in the Calendar app too.  

![Action Delete Parking in iOS](@site/static/img/map/context_menu_limited_parking_ios.png) ![Action Delete Parking in Android](@site/static/img/map/context_menu_limited_parking.png)

</TabItem>

<TabItem value="ios" label="iOS">

To remove the Parking point from the map, long-tap it and select **<Translate ios="true" ids="shared_string_dismiss"/>** in the opened [context menu](../map/map-context-menu.md#-add--delete-parking-point). If any reminder, it will be deleted in the Calendar app too. 

![Action Delete Parking in iOS](@site/static/img/map/context_menu_limited_parking_ios.png) 

</TabItem>

<TabItem value="android" label="Android">

To remove the Parking point from the map, long-tap it and select **<Translate android="true" ids="poi_action_delete"/>** in the opened [context menu](../map/map-context-menu.md#-add--delete-parking-point). If any reminder, it will be deleted in the Calendar app too. 

![Action Delete Parking in Android](@site/static/img/map/context_menu_limited_parking.png)

</TabItem>

</Tabs>