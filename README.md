# homebrew.sh
Install homebrew via Jamf without giving users admin rights

This script installs homebrew for the logged in user without requiring them to be an Administrator.

It is designed to be used in an MDM such as Jamf Pro.

Thanks to Richard Purves for the first version.

Thanks to all my users for feedback and improvements.


# brewEA.sh
This EA compliments the script to produce a Jamf extension attribute to record brew version.
It uses the same method of detecting device type and look in th esame place as the script.
 *If brew is installed in different locations this will not detect it!*
