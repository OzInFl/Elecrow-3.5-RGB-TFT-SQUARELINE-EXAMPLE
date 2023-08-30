SET(SOURCES screens/ui_Screen1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    images/ui_img_blankpgbkgnd_png.c
    images/ui_img_face1_png.c
    images/ui_img_face10_png.c
    images/ui_img_face11_png.c
    images/ui_img_face12_png.c
    images/ui_img_face2_png.c
    images/ui_img_face3_png.c
    images/ui_img_face4_png.c
    images/ui_img_face5_png.c
    images/ui_img_face6_png.c
    images/ui_img_face7_png.c
    images/ui_img_face8_png.c
    images/ui_img_face9_png.c
    images/ui_img_splashbkgnd2_png.c
    fonts/ui_font_LCD20at8BPP.c
    fonts/ui_font_LCD22at8BPP.c
    fonts/ui_font_LCD24at8BPP.c
    fonts/ui_font_LCD30at8BPP.c
    fonts/ui_font_Verdana11.c
    fonts/ui_font_Verdana12.c
    fonts/ui_font_Verdana14.c
    fonts/ui_font_Verdana16.c
    fonts/ui_font_Verdana18.c
    fonts/ui_font_Verdana24.c
    fonts/ui_font_Verdana36.c
    fonts/ui_font_Verdana48.c
    fonts/ui_font_Verdana8.c)

add_library(ui ${SOURCES})
