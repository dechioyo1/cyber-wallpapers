cmake_minimum_required(VERSION 3.19)
project(unsplash-wallpapers)

set(BACKGROUNDS
	unsplash-0.jpg
	unsplash-1.jpg
	unsplash-2.jpg
	unsplash-3.jpg
	unsplash-4.jpg
	unsplash-5.jpg
	unsplash-6.jpg
	unsplash-7.jpg
)

install(FILES ${BACKGROUNDS} DESTINATION /usr/share/backgrounds/cyber)
install(FILE ATTRIBUTION DESTINATION /usr/share/licenses/cyber-wallpapers/ATTRIBUTION.unsplash)
