FASTGRAPH FOR WINDOWS
An intuitive, high-performance graphics library

Windows graphics programming has traditionally involved using the Graphics
Device Interface (GDI) functions from the Windows Application Programming
Interface (API). More recently, the .NET framework introduced GDI+, an
enhanced version of GDI. GDI and GDI+ support other devices besides the
video display, but the price of this generality is speed. This translates
to the sluggish performance often associated with Windows graphics
applications.

Fastgraph solves this problem by providing a suite of more than 300 fast,
hand-optimized assembly language graphics functions that operate on
off-screen drawing surfaces called virtual buffers. GDI and GDI+ only come
into play when transferring the virtual buffer contents to the client area
of the application's window (this process is called blitting).

Fastgraph also works with but does not require the DirectDraw and Direct3D
components of Microsoft's DirectX. Fastgraph includes its own 3D software
rendering that is considerably faster than Direct3D software rendering. This
lets you write DirectX applications to use Direct3D hardware acceleration
if available, but if not, use Fastgraph's 3D software rendering without
sacrificing too much in terms of 3D performance.

Fastgraph is an ideal development tool for entertainment and educational
software, presentation graphics products, scientific and engineering
applications, CAD/CAM, animation, or any 32-bit Windows application that
demands robust graphics.


WHAT IS FASTGRAPH/LIGHT?

Fastgraph/Light is the evaluation version of Fastgraph. It includes virtually
all functions found in the retail version of Fastgraph, but it requires an
external run-time manager to run programs created with Fastgraph/Light. In
addition, you may not distribute programs created with Fastgraph/Light.

The retail version of Fastgraph does not use the run-time manager (that is,
it creates stand-alone programs). The retail version includes a royalty-free
distribution license for programs created with Fastgraph.


INSTALLING FASTGRAPH/LIGHT

The Fastgraph/Light distribution is normally supplied in a single ZIP file
named FGLWxxx.ZIP, where "xxx" is the version number. If you have an older or
incomplete version of Fastgraph/Light, you can download the current version
from http://www.fastgraph.com.

Follow these steps to install Fastgraph/Light:

1) Unzip all files in FGLWxxx.ZIP into a temporary directory.

2) Run the Fastgraph/Light Setup utility. Setup will install Fastgraph/Light
for the compiler you select, and optionally will install Fastgraph example
programs for that compiler. If you want to install Fastgraph/Light for more
than one compiler, just run Setup again.

3) Once you've installed Fastgraph/Light, you can delete the files in the
temporary directory.


SYSTEM REQUIREMENTS

Fastgraph/Light for Windows requires a Win32 system (Windows 95, 98, Me,
NT4, 2000, or XP). At least an 80486 microprocessor is required; a Pentium
is recommended. Fastgraph/Light works with but does not require Microsoft's
DirectX.


COMPILER SUPPORT

Fastgraph/Light for Windows supports these compilers:

   - Borland C++ (5.0 or later)
   - Borland C++Builder (1.0 or later)
   - Delphi (2.0 or later)
   - Microsoft Visual Basic (4.0 or later)
   - Microsoft Visual Basic .NET (2002 or later)
   - Microsoft Visual C# .NET (2002 or later)
   - Microsoft Visual C++ (2.2 or later)
   - PowerBASIC PB/DLL (6.0 or later)
   - Watcom C/C++ (11.0 or later)

The full Fastgraph product provides additional compiler support, as well as
legacy support for creating 16-bit Windows programs.


THE FASTGRAPH/LIGHT RUN-TIME MANAGER

Programs created with Fastgraph/Light require a run-time manager (FGW.EXE).
By default, Setup installs the run-time manager in the C:\FGW60 directory.
The run-time manager includes a help facility that describes its options in
detail, the primary differences between Fastgraph and Fastgraph/Light, the
terms of using Fastgraph/Light, and ordering information.

Once the Fastgraph/Light run-time manager is active, you can run programs
created with Fastgraph/Light just as you would any other Windows program.
This includes running programs from your compiler's integrated development
environment.

Note that the run-time manager is specific to Fastgraph/Light. Applications
created with the retail version run as stand-alone programs and do not use
the run-time manager.


FASTGRAPH HELP FILE

The Fastgraph/Light distribution includes the Fastgraph 6.0 for Windows help
file (FGW60.HLP). This help file is essentially a reproduction of the manuals
supplied with the retail version of Fastgraph. By default, Setup installs the
help file in the C:\FGW60 directory.

You can access the Fastgraph help file through the run-time manager, or as a
traditional Windows help file.


ADDITIONAL EXAMPLES

Besides the example programs supplied with Fastgraph/Light, more examples are
available from the "Demos" link on the Fastgraph web page (www.fastgraph.com).


FASTGRAPH/LIGHT PROGRAMS

Programs created with Fastgraph/Light for Windows will work for 30 days and
may not be distributed in any manner. If you use Fastgraph/Light for more
than 30 days, you really should consider buying the retail version!


UNINSTALLING FASTGRAPH/LIGHT

Run the UnInstall utility to uninstall Fastgraph/Light. By default, Setup
installs the UnInstall utility in the C:\FGW60 directory.

If you purchase Fastgraph for Windows after evaluating Fastgraph/Light, we
recommend uninstalling Fastgraph/Light before installing the retail version.


FASTGRAPH CONTACT INFORMATION

Ted Gruber Software, Inc.
PO Box 13408
Las Vegas, NV 89112
USA

voice: (702) 735-1980
  fax: (702) 735-4603

email: info@fastgraph.com
  web: http://www.fastgraph.com