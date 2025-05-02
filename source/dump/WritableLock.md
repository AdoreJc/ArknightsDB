# WritableLock

**Namespace:** ` `


## Fields

- `Boolean <isLocked>k__BackingField`


## Properties

- `Boolean isLocked`


## Methods

- `Boolean get_isLocked()`

- `Void set_isLocked(Boolean)`

- `IDisposable Lock()`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class WritableLock : IDisposable
{
	private Boolean <isLocked>k__BackingField; // 0x10

	public Boolean isLocked { get; set; }

	// RVA: 0x2f3cbe8 VA: 0x7595554be8
	public Boolean get_isLocked() { }
	// RVA: 0x2f3cbf0 VA: 0x7595554bf0
	private Void set_isLocked(Boolean value) { }
	// RVA: 0x2f3b64c VA: 0x759555364c
	public IDisposable Lock() { }
	// RVA: 0x2f3cbfc VA: 0x7595554bfc
	public Void Dispose() { }
	// RVA: 0x2f3b644 VA: 0x7595553644
	public Void .ctor() { }
}
```