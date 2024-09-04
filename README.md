# cpp20-compiler-tests
Visual Studio 2022 C++ projects for testing C++ 20 code compilation speed (modules vs classic code).

<h4>Projects:</h4>
<ul>
	<li><b>NoModules-NoPCH</b> - No C++ 20 modules, no Precompiled Header.</li>
	<li><b>NoModules-PCH</b> - No C++ 20 modules, with Precompiled Header.</li>
	<li><b>Modules-Cpp20</b> - C++ 20 modules, no Precompiled Header.</li>
	<li><b>Modules-Cpp20-PCH</b> - C++ 20 modules, with Precompiled Header.</li>
</ul>
<h4>Purpose:</h4>
<p>Finding out which options are better for the fastest compilation for projects with mixed code (C++ 20 modules with legacy headers).</p>
