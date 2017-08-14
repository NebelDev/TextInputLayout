# TextInputLayout
This example shows you how to use the TextInputLayout class present in the Android Support Library. It's a very useful class that provides an animation when you click on the TextInput component making the user input nicer. This widget is present starting from the version 22.2.0 of **Support Library**

### Usage:

Inside the **TextInputLayout** tag insert **TextInputEditText** tag. This last tag is just a sub-class of **EdiText** that implement more features like in this case to show animatin when the user tap on the input text field.

```xml
<android.support.design.widget.TextInputLayout
         android:layout_width="match_parent"
         android:layout_height="wrap_content">

     <android.support.design.widget.TextInputEditText
             android:layout_width="match_parent"
             android:layout_height="wrap_content"
             android:hint="@string/form_username"/>

 </android.support.design.widget.TextInputLayout>
 ```
 
