# flatpak
flatpak on linux


You can see which Flatpak applications you have installed with:

    flatpak list

You may have previously installed Flatpak applications and removed them, but the runtimes still remain. You can check this with:

    flatpak list -d --app --runtime




REMOVE CACHE


    ! pgrep -x flatpak && rm -r /var/tmp/flatpak-cache-*
