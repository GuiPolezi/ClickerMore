## 🖱️ ClickerMore
ClickerMore is a lightweight and efficient AutoClicker utility built in Java. It allows for continuous mouse click simulation with customizable intervals and global hotkey support.

## 🚀 Installation & Execution
You do not need Java installed to run the executable version available in the Releases section.

Navigate to the Releases tab of this repository.

Download the ClickerMore-v1.0-Portable.zip file.

Extract the contents to a folder of your choice.

Run the ClickerMore.exe file.

## 🛠️ How to Use
The system is designed to be simple and functional:

Set the Interval: In the "Interval (ms)" field, enter the wait time between each click (e.g., 3000 for 3 seconds).

Start the Clicker: - Click the START / STOP button on the interface.

OR use the global hotkey F6 on your keyboard (works even if the program is in the background).

Status Indicators: - 🔴 STATUS: STOPPED - The robot is on standby.

🟢 STATUS: RUNNING - The robot is clicking according to the set interval.

Randomization: The system automatically applies a small random variation to the click timing to simulate more human-like behavior.

### 💻 Compilation Requirements
If you wish to build the project from scratch:

JDK 21 or higher.

JNativeHook library (for global key capturing).

jpackage tool (included in the JDK) to generate the binary.