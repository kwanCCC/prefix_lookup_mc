cmake_minimum_required(VERSION 2.8.4)
project(prefix_lookup_mc)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES
        bitmap_v4.c
        bitmap_v4.h
        bitmap_v6.c
        bitmap_v6.h
        fast_lookup.c
        fast_lookup.h
        hash.c
        hash.h
        hmap.c
        hmap.h
        list.h
        main.c
        mb_node.c
        mb_node.h
        mm_color.c
        mm_color.h
        util.c
        util.h)

add_executable(prefix_lookup_mc ${SOURCE_FILES})