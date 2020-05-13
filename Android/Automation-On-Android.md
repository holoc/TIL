# Automation On Android

Android App Used: [Automate](https://llamalab.com/automate/)

Tasker Plugins:
* [AutoInput](https://joaoapps.com/autoinput/)
* [AutoTools](https://joaoapps.com/autotools/)
* [How-To Run AutoInput "UI Query" to grab info](https://www.reddit.com/r/tasker/comments/4nc0xc/how_to_run_a_ui_query_easily_on_any_screen_to/)

In searching how to create a pixel bot to automate various redundent tasks on my Android mobile device, I came across a few options to do this, but decided to settle on the Automate app to get the tasks done.

The idea is to use the plugin block with AutoInput plugin to identify the pixel colours at specific screen coordinates and AutoTools for OCR to detect specific text being displayed on the screen to pass on as a variable. The variables are then to be evaluated as a condition to trigger the next sequential action (i.e. touch screen input at x,y to move to the next screen).