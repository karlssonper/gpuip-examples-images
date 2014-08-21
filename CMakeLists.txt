cmake_minimum_required(VERSION 2.8)
project(gpuip_examples_images)
file(GLOB EXR_FILES "*.exr")
file(GLOB PNG_FILES "*.png")
install(FILES ${IMAGE_FILES} ${PNG_FILES}
  DESTINATION examples/images)