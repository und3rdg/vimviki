```javascript

    $.ajax({
      type: 'POST',
      url: url,
      data: formData,
      dataType: 'json',
      headers: headers,
      success: function(response) {

    },
    error: function(xhr, ajaxOptions, thrownError) {
      console.log("Uncaught Error.\n" + thrownError);
    }
    
```
