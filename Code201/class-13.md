## Read: 13 - Local Storage

In this read, we will talk about the difference between Storage in the

**THE PAST, PRESENT, AND FUTURE**

First, we want to talk about is:

**Cookies:** It is a store that saves your preferences on the Internet sites in terms of your preferences can be used for persistent local storage of small amounts of data, things that you prefer, and things that you pay attention to like: ``Clothes, Cars, Commodity, etc.``

She has more negatives than positives in her presence such as:

**1-**   **Cookies** are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

**2-**
**Cookies** are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

**3-**
**Cookies** are limited to about 4 KB of data — enough to slow down your application

---
</br>


**userData**: is allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.

**Gears**: an open-source browser plugin In 2007, Google launched aimed at providing additional capabilities in browsers

**Gears provides**: 
**1-** an API to an embedded SQL database based on SQLite. After obtaining permission from the user once

**2-** Gears can store unlimited amounts of data per domain in SQL database tables 



**HTML5 Storage**: it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies,

<br>

**Some Type of HTML5 storage support we use**

``Chrome 4.0+``  
``Opera 10.5+``
``FIREFOX 3.5+``
``SAFARI 4.0+``  
``ANDROID 2.0+``

**NOTE:** (if I want to access HTML5 Storage I can that by the local Storage object on the global window object)

We can check HTML5 Storage by type this code from using JavaScript code

``function supports_html5_storage() {``

``  try {``

``  return 'localStorage' in window && window``
``['localStorage'] !== null;``

``  } catch (e) {``

``    return false;``
``}``

``}``

We can also use **Modernizr** to detected support for HTML5 Storage by using Instead of writing this function yourself by typing this code

``if (Modernizr.localstorage) {``

``  // window.localStorage is available!``

``} else {``

``  storage or a third-party solution``

``}``

---

### USING HTML5 STORAGE

we can use HTML Storage based on a named key, then you can retrieve that data with the same key. The named key is a string it's deal with all of the data type in Javascript it also has strings, Booleans, integers, or floats but data actually stored as a **String** by using this code below

interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};

</br>

---

### TRACKING CHANGES TO THE HTML5 STORAGE AREA

We can be tracking changes in the HTML area by fired it coding it's declared using whenever 
``setItem(), removeItem(), or clear()`` is called and actually changes something, so if we want to track changes we can do it by type this code;

``if (window.addEventListener) {``

``  window.addEventListener("storage", handle_storage``

`` false);``

``} else {``

``  window.attachEvent("onstorage", handle_storage);``

``};``

---

### HTML5 STORAGE IN ACTION

In HTML storage it provides to us a beautiful feature when we use a web and we do something like filling data of play something There’s a small problem with the game: if you close the browser window mid-game, you’ll lose your progress. But with HTML5 Storage, we can save the progress locally, within the browser itself.

**We can start using it by type this code**

``function saveGameState() {``

``    if (!supportsLocalStorage()) { return false; }``
  
``  localStorage["halma.game.in.progress"] = gGameInProgress;``

``    for (var i = 0; i < kNumPieces; i++) {``

``  localStorage["halma.piece." + i + ".row"] = gPieces[i].row;``

``  localStorage["halma.piece." + i + ".column"] = gPieces[i].``

``column;``

``    }``

``    localStorage["halma.selectedpiece"``

 ``= gSelectedPieceIndex;``

``    localStorage["halma.selectedpiecehasmoved"]``

`` = gSelectedPieceHasMoved;``

``    localStorage["halma.movecount"] = gMoveCount;``
  

`` return true;``
``}``

---


_it was a simple explain briefly about Storage in HTML_

_In the end, I hope you enjoying reading, best wishes._

**Resource:** http://diveinto.html5doctor.com/storage.html