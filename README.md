# Find slots

### Usage
 
  Set environment
 
  ```
  make env
  ```
 
  Launch
 
  ```
  make
  ```
  Launch in background
 
  ```
  make hide
  ```
  
### Problem

How to get number of available slots out of html file? 

Slot.html is example of html with slots found and noslot.html html eith no slots found.

Line 196 <div data-duration="1".... >> if no slots stops at id='calendar' | if slots found continues with class="fc fc-unthemed fc-ltr"
-> tag "data-full" can only be found in slot.html and indicates slot find

-> Code could function but was not able to test it yet

### ADD

Run in background but not forever

install zenity on linux too
