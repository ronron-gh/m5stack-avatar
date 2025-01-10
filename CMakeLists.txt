
file(GLOB CODES "src/*.cpp")

idf_component_register(
  SRCS ${CODES}
  INCLUDE_DIRS "src/"
  REQUIRES M5Unified
)


