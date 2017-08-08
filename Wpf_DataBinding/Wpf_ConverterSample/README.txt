Implementation of databinding. From the back, i have implemented a converter in the Code-behind file called 
YesNoToBooleanConverter. As advertised, it just implements the two required methods, called Convert() and 
ConvertBack(). The Convert() methods assumes that it receives a string as the input (the value parameter) and 
then converts it to a Boolean true or false value, with a fallback value of false

In the XAML part of the program, i start off by declaring an instance of our 
converter as a resource for the window. We then have a TextBox, a couple of TextBlocks and a CheckBox control.
We bind the value of the TextBox to the TextBlock and the CheckBox control and using the Converter property 
and our own converter reference, we juggle the values back and forth between a 
string and a Boolean value, depending on what's needed. 