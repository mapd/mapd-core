set(utils_source_files
    StringLike.cpp
    Regexp.cpp
    ChunkIter.cpp
    ChunkAccessorTable.cpp
    DdlUtils.cpp
)

add_library(Utils ${utils_source_files})
target_link_libraries(Utils ${Boost_LIBRARIES} Shared)
