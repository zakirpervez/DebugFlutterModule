# DebugFlutterModule
A proof of concept (POC) to debug the Flutter module/app when it is invoked from the native side using browser.

## Debugging Steps
- Open the native application in your preferred IDE (e.g., Android Studio, VSCode etc).
- Run the native application on an emulator or a physical device.
- Open the Flutter module in your preferred IDE.
- Navigate to the Flutter module location in the terminal.
- Execute the `flutter attach` command. Wait for the command to sync with the files.
- Once syncing is complete, the terminal will display two URLs:
  - Dart VM Service: [http://127.0.0.1:52352/bChwaJ4Ez9Y=/]
  - Flutter DevTools debugger and profiler: [http://127.0.0.1:9101?uri=http://127.0.0.1:52352/bChwaJ4Ez9Y=/]
- Click/Copy Flutter DevTools debugger and profiler URL.
- The Flutter DevTools interface will open in your browser.
- Navigate to the "Debugger" tab, which will display the main.dart file.
- Set breakpoints as needed.

![Enjoy Debugging](https://media.giphy.com/media/QNFhOolVeCzPQ2Mx85/giphy.gif)

