# EasyAndFastGUI v2.0 - README

## Introduction
This is the README file for the code of EasyAndFastGUI v2.0. EasyAndFastGUI is an enhanced forex software that provides a user-friendly interface for trading and analyzing forex markets. This code provides an example of how to use the EasyAndFastGUI library in MQL5 to create a GUI with various elements such as buttons, labels, charts, and indicators. 

Please note that Forex Robot Easy Team is not the official developer of EasyAndFastGUI. We only provide a sample code that can work as described in the product. For detailed reviews and trading results of this product, please visit the official website of EasyAndFastGUI: [Forex Robot Easy](https://www.forexroboteasy.com).

## Code Description
The code is written in MQL5 and utilizes the EasyAndFastGUI library for creating a user interface. Here is a brief description of the code structure and functionality:

### Global Variables
- `g_GUI`: An instance of the `CEasyAndFastGUI` class, used for initializing and managing the GUI elements.

### Expert initialization function - `OnInit()`
- Initializes the GUI by calling the `Initialize()` method of the `CEasyAndFastGUI` class.
- Adds various GUI elements such as buttons, labels, charts, indicators, and inputs.
- Prints a success message if the GUI initialization is successful.

### Expert deinitialization function - `OnDeinit(const int reason)`
- Cleans up the GUI by calling the `Cleanup()` method of the `CEasyAndFastGUI` class.
- Prints a message to indicate that the GUI has been deinitialized.

### Expert tick function - `OnTick()`
- Updates the GUI elements such as labels, charts, and indicators by calling the respective update methods of the `CEasyAndFastGUI` class.

### Expert start function - `OnStart()`
- Runs an infinite loop to handle GUI events by calling the `HandleEvents()` method of the `CEasyAndFastGUI` class.
- Executes Buy or Sell orders based on button clicks.

## Product Description
EasyAndFastGUI v2.0 is an enhanced forex software that provides a user-friendly interface for trading and analyzing forex markets. It allows traders to easily place Buy or Sell orders, view account balance and equity, monitor price quotes, analyze charts with indicators, and set stop loss and take profit levels.

This product is developed by the official developer of EasyAndFastGUI. To find more information about this product, including detailed reviews and trading results, please visit the official website: [EasyAndFastGUI - Enhanced Forex Software](https://forexroboteasy.com/forex-robot-review/easyandfastgui-v2-0-enhanced-forex-software-review/).

Please note that Forex Robot Easy Team is not the official developer of this product. We only provide a sample code that demonstrates how to use the EasyAndFastGUI library. To find the official developer of this product, please refer to the MQL5 website.
