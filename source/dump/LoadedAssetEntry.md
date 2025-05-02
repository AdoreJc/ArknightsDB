# LoadedAssetEntry

**Namespace:** ` `


## Fields

- `String path`

- `Int32 refCnt`


## Methods

- `Void Alloc(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LoadedAssetEntry
{
	public String path; // 0x10
	public Int32 refCnt; // 0x18


	// RVA: 0x374bdac VA: 0x7595d63dac
	public Void Alloc(String path) { }
	// RVA: 0x374d070 VA: 0x7595d65070
	public static Void Release(LoadedAssetEntry inst) { }
	// RVA: 0x374d09c VA: 0x7595d6509c
	public Void .ctor() { }
}
```