# ubuntu-focal-20.04-pulseaudio_13.99.1_ldac_codec_griggorii_lgpl , ESD

Ubuntu 20.04 pulseaudio beta stable connect reconnect bluetooth headphones (напоминаю что проблема кроется в ядре торвальдса и нормально с командой pulseaudio -k && pulseaudio start работают нормально без такого сообщения как E: [pulseaudio] main.c: Too many arguments. Только эти ядра https://github.com/Griggorii/linux-image-5.9.3_amd64.deb_light_zstd_ultra_fast_kernel_wayland_fast/releases/tag/fast проблема этих исходников что они продаются в них еще не присоединено дополнительное ПО это всякие видео драйвера nvidia , anbox , dkms и многое другое и если ему надо будет исправить эту ошибку то пошлите его купить это ядро или терпите пока я не заключу соглашение с ит корпорациями , а там как поидет может и не один год заимет и не пять по факту у меня все готово я дал пояснение , ну а ваше дело маленькое терпеть всю молодость или что предпринять и заставить их купить это ядро ради комита спасающего миллионы денег для продажи тех же беспроводных аудио устройств. 

$ sudo tar xvpf pulseaudio_13.99.1_ldac_codec_griggorii_lgpl.tar.xz -C/

$ sudo dpkg -i libldacbt+dev_2.0.2.3-1_amd64.deb

Optional systemd pulseaudio.service

$ sudo mv pulseaudio.service '/usr/lib/systemd/user/pulseaudio.service'

$ rm -rf ~/.config/pulse/*

$ sudo alsa reload

$ sudo pulseaudio reload

check

$ gnome-control-center

reboot

<img src="https://github.com/Griggorii/ubuntu-focal-20.04-pulseaudio_13.99.1_ldac_codec_griggorii_lgpl/blob/master/LDAC-UBUNTU-20.0.4.png" alt="LDAC-UBUNTU-20.0.4.png">
