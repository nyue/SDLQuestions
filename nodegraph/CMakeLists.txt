add_executable(nodegraph
  main.cpp
  )

target_link_libraries(nodegraph
  # SDL3::Headers
  # SDL3::SDL3
  SDL3::SDL3-shared
  )