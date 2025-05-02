# MixerParamMgr

**Namespace:** ` `


## Fields

- `Boolean m_isDisposed`

- `Int64 <chunkID>k__BackingField`


## Properties

- `Int64 chunkID`


## Methods

- `Int64 get_chunkID()`

- `Void set_chunkID(Int64)`

- `Void EffectOnly_Modify(MusicParam, Single)`

- `Void SetCurrentChunk(Int64)`

- `Void ClearAll()`

- `Void Dispose()`

- `Void _ClearAllModification()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MixerParamMgr : IDisposable
{
	private LocalGenericPool`1 m_modificationPool; // 0x10
	private Boolean m_isDisposed; // 0x18
	private Int64 <chunkID>k__BackingField; // 0x20
	private List`1 m_modifications; // 0x28

	public Int64 chunkID { get; set; }

	// RVA: 0x21cafa0 VA: 0x75947e2fa0
	public Int64 get_chunkID() { }
	// RVA: 0x21cafa8 VA: 0x75947e2fa8
	private Void set_chunkID(Int64 value) { }
	// RVA: 0x21cafb0 VA: 0x75947e2fb0
	public Void EffectOnly_Modify(MusicParam param, Single value) { }
	// RVA: 0x21cb30c VA: 0x75947e330c
	public Void SetCurrentChunk(Int64 targetChunk) { }
	// RVA: 0x21caad4 VA: 0x75947e2ad4
	public Void ClearAll() { }
	// RVA: 0x21ca350 VA: 0x75947e2350
	public Void Dispose() { }
	// RVA: 0x21cb32c VA: 0x75947e332c
	private Void _ClearAllModification() { }
	// RVA: 0x21c95e4 VA: 0x75947e15e4
	public Void .ctor() { }
}
```