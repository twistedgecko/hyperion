add_subdirectory(hyperiond)
add_subdirectory(hyperion-remote)
if (ENABLE_V4L2)
	add_subdirectory(hyperion-v4l2)
endif (ENABLE_V4L2)
