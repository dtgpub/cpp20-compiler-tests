# cpp20-compiler-tests
Visual Studio 2022 C++ projects for testing C++ 20 code compilation speed (modules vs classic code).
Each project contains 500 headers and 500 source files for classic projects.
And 500 module interface files (*.ixx) and module implementation files (*.cpp) for C++ 20 module projects.
Each source file/module-implementation file has <b>#include "framework.h"</b>, which contains: <b>Windows.h</b>, <b>TlHelp32.h</b>, <b>iostream</b> for compilation speed testing purposes.
In projects with Precompiled Header, <b>"pch.h"</b> is included instead of direct <b>"framework.h"</b> inclusion.

<h4>Projects:</h4>
<ul>
	<li><b>NoModules-NoPCH</b> - No C++ 20 modules, no Precompiled Header.</li>
	<li><b>NoModules-PCH</b> - No C++ 20 modules, with Precompiled Header.</li>
	<li><b>Modules-Cpp20</b> - C++ 20 modules, no Precompiled Header.</li>
	<li><b>Modules-Cpp20-PCH</b> - C++ 20 modules, with Precompiled Header.</li>
</ul>
<h4>Purpose:</h4>
<p>Finding out which options are better for the fastest compilation for projects with mixed code (C++ 20 modules with legacy headers).</p>
