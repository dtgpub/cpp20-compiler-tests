# cpp20-compiler-tests
Visual Studio 2022 C++ projects for testing C++ 20 code compilation speed (modules vs classic code).

Projects:
	NoModules-NoPCH			No C++ 20 modules, no Precompiled Header.
	NoModules-PCH			No C++ 20 modules, with Precompiled Header.
	Modules-Cpp20			C++ 20 modules, no Precompiled Header.
	Modules-Cpp20-PCH		C++ 20 modules, with Precompiled Header.

Purpose: Finding out which options are better for the fastest compilation for projects with mixed code (C++ 20 modules + legacy headers).
