# CompilationRelaxationsAttribute

**Namespace:** `System.Runtime.CompilerServices`


## Fields

- `Int32 m_relaxations`


## Properties

- `Int32 CompilationRelaxations`


## Methods

- `Int32 get_CompilationRelaxations()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.CompilerServices
public class CompilationRelaxationsAttribute : Attribute
{
	private Int32 m_relaxations; // 0x10

	public Int32 CompilationRelaxations { get; }

	// RVA: 0x5fd899c VA: 0x75985f099c
	public Void .ctor(Int32 relaxations) { }
	// RVA: 0x5fd89c4 VA: 0x75985f09c4
	public Void .ctor(CompilationRelaxations relaxations) { }
	// RVA: 0x5fd89ec VA: 0x75985f09ec
	public Int32 get_CompilationRelaxations() { }
}
```