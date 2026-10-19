# PHOEHTWE 2D — Android Studio project

This project wraps the supplied Excel workbook in an offline Android app named **PHOEHTWE 2D**.

## Build an APK
1. Install Android Studio on a computer.
2. Open this project folder in Android Studio.
3. Allow Gradle sync and install Android SDK Platform 35 if prompted.
4. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Android Studio will show the APK location. Transfer it to your Android phone and install it.

## Included
- Workbook sheets imported from the provided Excel file.
- Tap a cell to edit; edits are saved locally on the device.
- Add a blank row, export a JSON backup, import a JSON backup, or reset to original workbook.

## Important limitations
- This is an offline starter app, not a full Excel engine. Excel formulas are displayed as formula text and are not recalculated automatically.
- The app stores changes in the app's local browser storage. Export a JSON backup before clearing app data or uninstalling.
- Review all calculations and financial records before relying on them.
