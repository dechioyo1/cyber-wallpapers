cmake_minimum_required(VERSION 3.5)
project(unsplash-backgrounds)

set(BACKGROUNDS
	unsplash-0.jpg
	unsplash-1.jpg
	unsplash-2.jpg
	unsplash-3.jpg
	unsplash-4.jpg
	unsplash-5.jpg
	unsplash-6.jpg
)

install(FILES ${BACKGROUNDS} RUNTIME DESTINATION /usr/share/backgrounds/cyber)
