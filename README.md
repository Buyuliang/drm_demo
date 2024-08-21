# drm_demo
alpine add libdrm-dev libpng-dev

gcc -o display_png display_png.c `pkg-config --cflags --libs libdrm libpng` -lpng -Wall -O0 -g

display_png <card0> <png_file_path>

注：PNG 图片显示异常需要使用画图工具另存为 PNG
