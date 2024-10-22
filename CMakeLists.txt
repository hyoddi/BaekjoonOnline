cmake_minimum_required(VERSION 3.5.0)
project(
    Baekjoonalgorithm # 프로젝트 이름
    VERSION 1.0.0 # 프로젝트 버전
    DESCRIPTION "백준 알고리즘 풀이" # 프로젝트 설명
    LANGUAGES C # 사용할 언어
    )

set(CMAKE_C_STANDARD)

enable_testing()
include(CPack)


add_subdirectory(src)