# AttributeInfo

**Namespace:** ` `


## Fields

- `AttributeUsageAttribute _usage`

- `Int32 _inheritanceLevel`


## Properties

- `AttributeUsageAttribute Usage`

- `Int32 InheritanceLevel`


## Methods

- `AttributeUsageAttribute get_Usage()`

- `Int32 get_InheritanceLevel()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : 
private class AttributeInfo
{
	private AttributeUsageAttribute _usage; // 0x10
	private Int32 _inheritanceLevel; // 0x18

	public AttributeUsageAttribute Usage { get; }
	public Int32 InheritanceLevel { get; }

	// RVA: 0x6102270 VA: 0x759871a270
	public Void .ctor(AttributeUsageAttribute usage, Int32 inheritanceLevel) { }
	// RVA: 0x6104a10 VA: 0x759871ca10
	public AttributeUsageAttribute get_Usage() { }
	// RVA: 0x6104a18 VA: 0x759871ca18
	public Int32 get_InheritanceLevel() { }
}
```