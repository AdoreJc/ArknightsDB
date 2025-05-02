# AssemblyLoadEventArgs

**Namespace:** `System`


## Properties

- `Assembly LoadedAssembly`


## Methods

- `Assembly get_LoadedAssembly()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class AssemblyLoadEventArgs : EventArgs
{
	private readonly Assembly <LoadedAssembly>k__BackingField; // 0x10

	public Assembly LoadedAssembly { get; }

	// RVA: 0x6023380 VA: 0x759863b380
	public Void .ctor(Assembly loadedAssembly) { }
	// RVA: 0x60233f4 VA: 0x759863b3f4
	public Assembly get_LoadedAssembly() { }
}
```