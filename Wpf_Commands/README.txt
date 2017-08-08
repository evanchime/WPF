Implementation of WPF Commands. A very simple interface with a couple of buttons and a TextBox control. 
The first button will cut to the clipboard and the second one will paste from it. 
In Code-behind, we have two events for each button: One that performs the actual action, which name ends with _Executed, and then the CanExecute events. 
In each of them, you will see that I apply some logic to decide whether or not the action can be executed and then assign it to the return value CanExecute on the EventArgs. 
