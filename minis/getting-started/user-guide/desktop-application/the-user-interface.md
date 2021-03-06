# The User Interface

{% hint style="info" %}
The desktop application version for this guide is 1.1.0. If you have the previous version, you may have different user interface. Even if the latest version of application has quite more functionality, you can still follow the guide and learn how to use for the older versions.
{% endhint %}

The main window of the application can be seen below:

![](../../../../.gitbook/assets/image%20%2836%29.png)

1. This indicates the desktop application software together with the usb connection status of the device. If the device is connected, it will show **"Minis 1.1.0 \(Connected\)"** and theme will be **green**. Otherwise it will show **"Minis 1.1.0 \(Disconnected\)"** and the theme will be **red**.
2. These arrows hide the left and right control panels to increase the scope area.
3. The scope area includes the buffer navigator and the graph that display the signal values in the time domain. The buffer navigator shows the complete buffer. In addition, the signal that is visible in the graph is highlighted in the navigator. The graph shows both the time values and volt values for the channels. For other details about buffer, check [**Buffer Settings**](buffer-settings.md). For other details about scope, check [**Scope Settings**](scope-settings/).
4. Play/Pause button. It starts/stops the device.
5. Autoset button. The system tries to find the best volt/div and time/div values for better observation.
6.  In this area, you can select the trigger source \(CH1/CH2\), trigger mode\(Auto, Normal, Single\) and trigger edge\(Rising, Falling\). You can find other details in the [**Trigger** ](scope-settings/trigger.md)section.
7. This tabs help you to select the signals that you want to change the settings of.
8. Zoom in & zoom out buttons change the volt/div for the selected signal in part 7. You can also type the desired volt/div in the box. 
9. Zoom in & zoom out buttons change the time/div for all the signals. You can also type the desired time/div in the box. For further details check [**Volt/div & Time/div Settings**](scope-settings/volt-div-and-time-div-settings.md).
10. The user can enable/disable the AC Coupling and the display of the selected signal in part 7.
11. The measurements\(Frequency, Period, PP, Max, Mean, Min, Rms, Duty Cycle\) for the signals will be shown here.
12. This area consists of 3 tabs: Signals, Measurements and Functions. In the "Signals" tab, you can see the channels and additional signals which are the output of the math functions. You can change the color of all signals, you can see the equation of the math signals and you can delete the math signals. In the "Measurements" tab, you can add measurements for all the signals. To learn more about the measurements, check the page [**Measurements**](measurements.md). In the "Functions" tab, you can make simple math operations on the signals. Check the page [**Simple Functions**](simple-functions.md) ****for other information.
13. This floating action button opens another set of control buttons. You will see the explanation for these buttons in the upcoming pages.

The below image shows the floating action buttons in the open state.

![](../../../../.gitbook/assets/image%20%2890%29.png)

1. It opens/closes other floating action buttons.
2. It opens/closes export options. 2.1 It exports the view that is visible between the left and right control panels as PNG. 2.2 It exports a PDF that includes a PNG\(same as 2.1\) and a table\(values are from the measurement table\) 2.3 It exports the time-domain and frequency-domain\(if visible\) values as XLSX. 2.4 It exports the time-domain and frequency-domain\(if visible\) values as MAT file\(for matlab\).
3. It opens the **Functions** page. For details, check [**Advanced Functions**](custom-functions.md)**.**
4. It opens the [**Contact** ](contact.md)page.
5. It opens/closes other settings related floating action buttons.

   5.1 It opens the [**Preferences** ](preferences.md)page.  
   5.2 It opens the [**Firmware Update**](firmware-update.md) page.  
   5.3 It checks whether a newer version of the software application exists. Check [**Software Update**](software-update.md) ****for more information**.**

6. It opens the Compocket's [**website**](https://compocket.com/). 

