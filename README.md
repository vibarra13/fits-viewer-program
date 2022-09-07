# fits-viewer-program
# A python application to view fits files.

# Hi! My name is Victor Ibarra, and I am a student coder at George Mason University.

# My passions are coding and astronomy, so I chose to make a project that would include a lot of both. This is a project to showcase the use of FITS files and numpy
# arrays. The packages I will be using are Astropy, matplotlib and NumPy. I will be using radio FITS files acquired from a single imaging session, all pointed at the
# same location in space which contains a potential pulsar emitting radio waves. This program asks for user input. It will ask the user to input their own fits files, 
# but I will be using some provided by the University of Sydney for my own tests. Whether users want to view one fits file, or stack several fits files 
# and view the resulting stacked image, it is all up to them.
# I will stack the images together using the mean of each pixel in all the images. I will make the observations and final notes in the end.

# The main features of this project will be: 
# 1. Reading in fits image files based on user input
# 2. Plotting image(s) data on a 2-d graph
# 3. Getting the coordinates of the brightest points on an image
# 4. Producing an average stack of image files (only when selecting multiple files)
# 6. Providing end of project notes to compare/contrast stacking vs. not stacking

# The Findings

# In this project, I found that it was game-changing to use python and its libraries to create a visual representation of a large group of data.
# Usually, datasets are intimidating and hard to work with by hand, and even with excel. That said, I enjoy organizing data and reconstructing it to create
# visually appealing information that also makes sense to look at. Each fits file had the brightest point at a different location. After stacking my example files, the 
# brightest point ended up at coordinates (100, 100), even though in some individual images the brightness of those coordinates was similar to the area around it.
# This shows the power of stacking in astrophotographs, since improving the signal to noise ratio (SnR) allows us to uncover what's hiding in the data. Essentially,
# the SnR just means stacking photos together using the average of each pixel, allowing the important data (the pulsar) to stand out more than the image noise does.
# Image noise is normal when it comes to photographs, but in imaging outer space, noise can become problematic really quickly. More info on noise in images on my 
# website! 

# This project allowed me to take my two favorite hobbies, astronomy and coding, and mash them together to create an exciting, yet somewhat challenging project.
# My favorite part of this project was learning to use and modify NumPy arrays because I love working with datasets in python. The packages provided in
# python make this a much better learning experience than if I were to be using lists, even if they are the same concept. I also enjoyed creating a simple
# 2-d plot to demonstrate the results of stacking images.

# Sources
# https://fits.gsfc.nasa.gov/fits_primer.html#:~:text=HDUs,point%20numbers%20using%20IEEE%20representations. information on HDU's in fits files
# https://matplotlib.org/stable/tutorials/colors/colormaps.html colors for the plot
# https://www.youtube.com/watch?v=EBP1ox3SQfA for try-catch statement guide
# University of Sydney for the image files I used
