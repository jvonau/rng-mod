# rng-mod
systemd unit file for running rng-tools' rngd early in boot process

edit /etc/init.d/rng-tools changing PIDFILE=/run/rngd.pid

copy rng-tools.service in /etc/systemd/system/rng-tools.service

sudo systemctl enable rng-tools.service

sudo reboot

