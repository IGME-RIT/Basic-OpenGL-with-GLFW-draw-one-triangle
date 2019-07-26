Documentation Author: Niko Procopi 2019

This tutorial was designed for Visual Studio 2017 / 2019
If the solution does not compile, retarget the solution
to a different version of the Windows SDK. If you do not
have any version of the Windows SDK, it can be installed
from the Visual Studio Installer Tool

Welcome to the One-Triangle Tutorial!
Prerequesites: Window creation

In order to draw a triangle, we need to make three vertices
that are in the triangle. Each vertex will have an X, Y, and Z
position. Z will be zero for all, because this is a 2D triangle

	GLfloat vertices[] =
	{
		// POSITION		

		// X, Y, Z position of vertex #1
		-0.5f, -0.5f, 0.0f,		
		
		// X, Y, Z position of vertex #2
		0.5, -0.5f, 0.0f,		
		
		// X, Y, Z position of vertex #3
		0.0f, 0.5f, 0.0f		
	};
	
One thing to be aware of:
This is an array called "vertices", but it is an array of 
nine floats. These nine floats make three vertices. Remember that

This particular tutorial is filled to the brim with comments, so 
further explanation may not be needed here. However, keep in the habit
of checking README!.txt, especially for the "more graphics" section,
where there will be more information here than there will be in comments