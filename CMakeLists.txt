cmake_minimum_required (VERSION 3.8)
project ("my-redis")

# 将源代码添加到此项目的可执行文件。
add_executable (server 
				"server.cpp"
				"avl.cpp" 
				"avl.h"
				"common.h"
				"hashtable.cpp"
				"hashtable.h" 
				"heap.cpp"
				"heap.h"
				"list.h" 
				"thread_pool.cpp"
				"thread_pool.h"
				"zset.cpp"
				"zset.h")

add_executable(client 
				"client.cpp"
				"avl.cpp" 
				"avl.h"
				"common.h"
				"hashtable.cpp"
				"hashtable.h" 
				"heap.cpp"
				"heap.h"
				"list.h" 
				"thread_pool.cpp"
				"thread_pool.h"
				"zset.cpp"
				"zset.h")
