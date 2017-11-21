# Fields


Fields can be accessed via the `Fields` array. Each field has a number of methods - it may not always make sense to invoke a given method on a field.

## Field methods

{% method %}
### Click

Will click on the given field.


{% sample lang="js" %}
Clicking on a button.
```javascript
Fields["mybutton"].click();
```

#### Support

  - ChromeDriver
  - IEDriver
  - JavaDriver
  - NativeDriver

{% endmethod %}
