# raspbian_dynhost
Dynamic update from Raspberry pi when using OVH Dynhost service

Obviously I took the original script elsewhere but it was not running at all because of quotes.

This one works and has been tested.

There is no simple quotes >'< because it brings problem when manipulating this script between OSs' (Win, linux ...)


Create the dynhost entry in OVH service for the host you need.

ex: http://api.yoursupersite.com

Create an entry in your router with appropriate ports id

Modify this script with your ovh credentials 

Just place this script (file with no extension) in cron.hourly directory (make it executable if needed)


I hope it helps.
