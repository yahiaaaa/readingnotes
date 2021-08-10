# LOCAL STORAGE FOR WEB APPLICATIONS

![image text](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5d/AppLSAC_Basic.svg/1200px-AppLSAC_Basic.svg.png  "image Title")

For native applications the operating system typically provides an abstraction layer to save and store data from and to the applications you can also embed your own database, invent your own file format, or any number of other solutions.

web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

### Storage Event
To keep track of the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. Example:

window.addEventListener("storage", handle_storage);


### INTRODUCING HTML5 STORAGE

So what is HTML5 Storage? Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

 * USING HTML5 STORAGE
it based on named key/value pairs. The named key is always a string If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

* setItem , using to make a new item
 * getItem , using to get item that was already exists Calling setItem() with a named key that already exists will silently overwrite the previous value. Calling getItem() with a non-existent key will return null rather than throw an exception.
* removing the value for a given named key,(removeItem)
* clearing the entire storage area()

function supports_html5_storage() {

  try {
  
    return 'localStorage' in window && window['localStorage'] !== null;
    
  } catch (e) {
  
    return false;
    
  }
}
