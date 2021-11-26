
#
# Main component of TF Micro project
#

idf_component_register(
    SRCS esp/main.cc main_functions.cc model_settings.cc app_camera_esp.c  image_provider.cc person_detect_model_data.cc
    INCLUDE_DIRS "")
