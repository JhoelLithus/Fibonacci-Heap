# Estructura-de-Datos-IV

 ## Autor: Jhoel Huallpar Dorado ##

# FIBONACCI HEAP #

# Description
This is a simple fibonacci heap, supporting the standard operations:

* Insert
* Merge
* Extract Minimum
* Find Minimal

	We also have a non-standard find function; this is only for testing and should not be used in production as finding in a heap is O(n).

	Fibonacci heaps are slow and have significant storage overheads (4 pointers per node, plus an int and a bool for housekeeping.) They have a better complexity than binomial heaps only when you are doing significantly more merges or decrease key operations than extract minimum operations.

	This implementation should show how Fibonacci heaps work; it is not intended to be highly performant.

# Dependencies (windows)
	
	In order to use the code in Windows, you must necessarily install the mingw and the graphviz; which is in the folder "Software required".

	Once installed the MinGw, we go to the installation path #C: \ MinGW \ mingw32 \ bin #
	In Search, search and select: System (Control Panel) Click on the Advanced System Settings link. Click on Environment variables. In the System Variables section, look for the PATH environment variable and select it. Click on Edit If the PATH environment variable does not exist, click New. In the Edit System Variable (or New System Variable) window, copy the following C: \ MinGW \ mingw32 \ bin Click OK.

	For more information on how to install and configure MinGW go to the video link, which is at the end of this document.

# Compilation from the Console (windows)

	To compile it properly you must move inside the console to the folder where it contains the source code.
	
	*************************************
	g++ FibonacciHeap.cpp -o FibHep.exe
	*******************************
	Then you compile the document ".exe" generated by the console.
	*************************************
	FibHep.exe
	*******************************
	Once you have done this step you go to the folder where the documents of the "fibonacci heap" are located and you will realize that it generated some images; in these images are plotted the "Fibonacci Heap"

# References
 
	* https://www.cs.usfca.edu/~galles/JavascriptVisual/FibonacciHeap.html  //Demo Online
	* https://www.geeksforgeeks.org/fibonacci-heap-set-1-introduction/
	* http://web.karabuk.edu.tr/hakankutucu/CME222/MIT[1].Press.Introduction.to.Algorithms.2nd.Edition.eBook-TLFeBOOK.pdf
	* https://github.com/robinmessage/fibonacci
	* https://www.youtube.com/watch?v=mnIBSMvNSBk
	* https://www.youtube.com/watch?v=tpmiDdMllg8
	* https://www.youtube.com/watch?v=sXW2VLrQ3Bs  //INSTALLATION OF THE MINGW

# University
	Universidad La Salle - Arequipa	
 
 ## Arequipa - Perú ##
 ## Date:09/07/2019 ##