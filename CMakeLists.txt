add_library(implot SHARED
    implot_items.cpp implot.cpp implot.h implot_internal.h)
target_include_directories(implot PUBLIC .)
target_link_libraries(implot PRIVATE imgui)
