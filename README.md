# Android-Country_Code_Picker
This application is used to pick a country code with country flag in a list.

1. Add CCP view to layout

2. Add AppCompatEditText view to layout

3. register the AppCompatEditText using registerPhoneNumberTextView(AppCompatEditText) we can use TextView instead of AppCompatEditText 
also.

4. Let the magic happens ;)

Here the more details step:

1. Add CCP to layout using the following:

```java
<github.hemathajay.com.picker.CountryCodePicker
      android:id="@+id/ccp"
      android:layout_width="wrap_content"
      android:layout_height="wrap_content" />
```

2. Add AppCompatEditText view to layout:


<android.support.v7.widget.AppCompatEditText
       android:id="@+id/phone_number_edt"
       android:layout_width="match_parent"
       android:layout_height="wrap_content"
       android:hint="phone"
       android:inputType="phone"/>



