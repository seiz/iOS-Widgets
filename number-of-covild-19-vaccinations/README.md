# Number of Covid 19 vaccinations
![Preview light](https://raw.githubusercontent.com/ThisIsBenny/iOS-Widgets/main/number-of-covild-19-vaccinations/previewLight.jpeg)
![Preview dark](https://raw.githubusercontent.com/ThisIsBenny/iOS-Widgets/main/number-of-covild-19-vaccinations/previewDark.jpeg)
![Preview light](https://raw.githubusercontent.com/ThisIsBenny/iOS-Widgets/main/number-of-covild-19-vaccinations/previewLight2.jpeg)
![Preview dark](https://raw.githubusercontent.com/ThisIsBenny/iOS-Widgets/main/number-of-covild-19-vaccinations/previewDark2.jpeg)
![Preview light](https://raw.githubusercontent.com/ThisIsBenny/iOS-Widgets/main/number-of-covild-19-vaccinations/previewLight3.jpeg)
![Preview dark](https://raw.githubusercontent.com/ThisIsBenny/iOS-Widgets/main/number-of-covild-19-vaccinations/previewDark3.jpeg)

This widget displays the number of Covid 19 vaccinations. In the small and medium widet, the total number for all states is displayed by default. By entering the state name in the widget parameters, you can switch to the number for the state in the small widget. In the medium widget, by entering the state name, the numbers of the state are displayed next to those of the whole Germany.
The large widget shows all 16 states and the total.

_The widget is using a cache for 4 hours to protect the server from too much load. Since the data is updated by the RKI itself only once a day, this should be sufficient. If you like to perform a force update, you can use this URL: `scriptable:///run/number-of-covild-19-vaccinations?forceUpdate=true` or click [here](https://open.scriptable.app/run/number-of-covild-19-vaccinations?forceUpdate=true)_

[[Download]](https://raw.githubusercontent.com/ThisIsBenny/iOS-Widgets/main/number-of-covild-19-vaccinations/number-of-covild-19-vaccinations.js)

## Optional Setup
Enter the name of you state in the Widget-Parameter:

![Setup](https://raw.githubusercontent.com/ThisIsBenny/iOS-Widgets/main/number-of-covild-19-vaccinations/setup.jpeg)

If you like to show the total values in million instead of thousand, you can add an additional 1 to the Widget-Parameter, which has to be separated by a comma: `Nordrhein-Westfalen,1`. If you do not want to specify a state, you only have to enter a `1`

![Setup](https://raw.githubusercontent.com/ThisIsBenny/iOS-Widgets/main/number-of-covild-19-vaccinations/alternative.jpeg)

## Notice
Source of the data is the RKI: https://www.rki.de/DE/Content/InfAZ/N/Neuartiges_Coronavirus/Daten/Impfquoten-Tab.html

The Excel provided by the RKI is accessible via an API for the widget: https://github.com/ThisIsBenny/rki-vaccination-data

## Contributors
- [Seiz](https://github.com/Seiz)
