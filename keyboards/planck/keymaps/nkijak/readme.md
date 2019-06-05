# The nkijak Planck Layout

## building on ubuntu linux (XPS-9800)
1. `util/docker_build.sh planck/rev6:nkijak`
1. `dfu-util -a 0 -d 0483:df11 -s 0x8000000 -R -D planck_rev6_nkijak.bin` prefix with `sleep 4 &&` if planck is only keyboard
