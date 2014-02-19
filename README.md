pjax-example
============

Minimal example for sending data through PJAX using PHP


Issues to be resolved:
======================
I have been trying to send some data (which may be gathered using HTML FORM, or some arbitrary JS variable) to slave.php page called from master.php via PJAX. One way that i understand is to use jQuery to append data to the URL parameters and retrieve them in $GET in slave.php. I instead want to use $_POST.
