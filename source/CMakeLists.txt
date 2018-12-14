cmake_minimum_required(VERSION 3.10)

project(etcpack LANGUAGES CXX)

add_executable(etcpack
	etcdec.cxx
	etcpack.cxx
	image.cxx
	image.h
)

