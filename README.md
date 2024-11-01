# Hot tracking listbox

Hot tracking is a feature that provides feedback to the user when the mouse pointer passes over the LIST control. With the Hot tracking property set to on, the LIST control responds to mouse movement by highlighting the row over which the mouse pointer is positioned. For a better understanding, [watch the short video](https://github.com/user-attachments/assets/c52d2820-fb3d-41c9-9416-8d26b8c6a1a5).

  
### Hot tracking listbox class
Adds the following functionality to LIST controls (those with FROM(Queue)):
- Hot tracking: highlight the row over which the mouse pointer is positioned.
- 3 predefined hot tracking modes: TextColor, Hyperlink and LightBox (all these modes can be seen in the video).
- Ability to change available hot tracking modes or create your own.
- Hover selection: automatically select a row when the mouse pointer remains over the row for a few seconds.
- Single click activation: use a single click instead of a double click (eg to call a form).
  
The class takes into account scrolling the list, filtering and reloading the queue.


### Hot tracking BrowseBox template
The global Hot tracking BrowseBox extension enables hot tracking for all the browses in an app.  
However, in order for the browsebox to highlight hot rows, you must manually set the style property to TRUE for the browse columns in the Listbox Designer.
- The template optionally shows a list of browseboxes that do not have columns with the Style property set to TRUE.
- Allows to control hot tracking from INI file or another repository.


### Requirements
- C6.3 and higher
- ABC and Clarion template chains


### Dependencies
- [winapi](https://github.com/mikeduglas/winapi)
- [printf](https://github.com/mikeduglas/printf)


### Contacts
mikeduglas@yandex.ru

[Buy now](https://www.clarionshop.com/checkout.cfm?pid=1691&q=1)
