Copy the files from etc-nixos to /etc/nixos

Copy the files from home-config to /home/&lt;user&gt;/.config

Run nixos-rebuild switch

Run the following to enroll a fingerprint
sudo fprintd-enroll $env.USER

reboot
