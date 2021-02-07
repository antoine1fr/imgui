add_library(imgui STATIC
  "${CMAKE_CURRENT_LIST_DIR}/imgui.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/imgui_draw.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/imgui_tables.cpp"
  "${CMAKE_CURRENT_LIST_DIR}/imgui_widgets.cpp")
target_include_directories(imgui
  PUBLIC
  "${CMAKE_CURRENT_LIST_DIR}")
