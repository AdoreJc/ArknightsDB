# CharacterProduct

**Namespace:** ` `


## Fields

- `Int64 m_startTime`

- `Int64 m_endTime`

- `Single m_basicProgress`

- `Boolean <running>k__BackingField`


## Properties

- `Int64 startTime`

- `Int64 endTime`

- `Single basicProgress`

- `Int32 creditPerClue`

- `Boolean running`


## Methods

- `Int64 get_startTime()`

- `Int64 get_endTime()`

- `Single get_basicProgress()`

- `Int32 get_creditPerClue()`

- `Boolean get_running()`

- `Void set_running(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CharacterProduct : ICharacterClueProduct
{
	private Int64 m_startTime; // 0x10
	private Int64 m_endTime; // 0x18
	private Single m_basicProgress; // 0x20
	private Boolean <running>k__BackingField; // 0x24

	public Int64 startTime { get; }
	public Int64 endTime { get; }
	public Single basicProgress { get; }
	public Int32 creditPerClue { get; }
	public Boolean running { get; set; }

	// RVA: 0x3de185c VA: 0x75963f985c
	public Void .ctor(Int64 startTime, Int64 endTime, Single basicProgress) { }
	// RVA: 0x3de74bc VA: 0x75963ff4bc
	public Int64 get_startTime() { }
	// RVA: 0x3de74c4 VA: 0x75963ff4c4
	public Int64 get_endTime() { }
	// RVA: 0x3de74cc VA: 0x75963ff4cc
	public Single get_basicProgress() { }
	// RVA: 0x3de74d4 VA: 0x75963ff4d4
	public Int32 get_creditPerClue() { }
	// RVA: 0x3de7524 VA: 0x75963ff524
	public Boolean get_running() { }
	// RVA: 0x3de752c VA: 0x75963ff52c
	public Void set_running(Boolean value) { }
}
```