# CompatibleComparer

**Namespace:** `System.Collections.Specialized`


## Fields

- `IComparer _comparer`

- `IHashCodeProvider _hcp`


## Properties

- `IComparer Comparer`

- `IHashCodeProvider HashCodeProvider`


## Methods

- `Boolean Equals(Object, Object)`

- `Int32 GetHashCode(Object)`

- `IComparer get_Comparer()`

- `IHashCodeProvider get_HashCodeProvider()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Collections.Specialized
internal class CompatibleComparer : IEqualityComparer
{
	private IComparer _comparer; // 0x10
	private static IComparer defaultComparer; // 0x0
	private IHashCodeProvider _hcp; // 0x18
	private static IHashCodeProvider defaultHashProvider; // 0x8

	public IComparer Comparer { get; }
	public IHashCodeProvider HashCodeProvider { get; }
	public static IComparer DefaultComparer { get; }
	public static IHashCodeProvider DefaultHashCodeProvider { get; }

	// RVA: 0x640e618 VA: 0x7598a26618
	internal Void .ctor(IComparer comparer, IHashCodeProvider hashCodeProvider) { }
	// RVA: 0x640eea0 VA: 0x7598a26ea0
	public Boolean Equals(Object a, Object b) { }
	// RVA: 0x640f0a0 VA: 0x7598a270a0
	public Int32 GetHashCode(Object obj) { }
	// RVA: 0x640f1ac VA: 0x7598a271ac
	public IComparer get_Comparer() { }
	// RVA: 0x640f1b4 VA: 0x7598a271b4
	public IHashCodeProvider get_HashCodeProvider() { }
	// RVA: 0x640dd80 VA: 0x7598a25d80
	public static IComparer get_DefaultComparer() { }
	// RVA: 0x640dc9c VA: 0x7598a25c9c
	public static IHashCodeProvider get_DefaultHashCodeProvider() { }
}
```