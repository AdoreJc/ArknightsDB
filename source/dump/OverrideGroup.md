# OverrideGroup

**Namespace:** ` `


## Fields

- `OverrideType m_type`

- `Int32 m_maxStackCnt`

- `Int32 m_maxValidStackCnt`


## Methods

- `Boolean Add(Buff)`

- `Void Remove(Buff)`

- `Int32 SafeCount()`

- `Void UpdateMe()`

- `Void Clear()`

- `Void ExtendStackCnt(Int32)`

- `Void SetMaxStackCnt(Int32)`

- `Boolean _DoAddInternal(Buff)`

- `Void _DoUpdateInternal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class OverrideGroup
{
	private PriorityQueue`1 m_queue; // 0x10
	private OverrideType m_type; // 0x18
	private Int32 m_maxStackCnt; // 0x1c
	private Int32 m_maxValidStackCnt; // 0x20


	// RVA: 0x3f7febc VA: 0x7596597ebc
	public Void .ctor(Buff initialBuff) { }
	// RVA: 0x3f8000c VA: 0x759659800c
	public Boolean Add(Buff buff) { }
	// RVA: 0x3f80544 VA: 0x7596598544
	public Void Remove(Buff buff) { }
	// RVA: 0x3f800c4 VA: 0x75965980c4
	public Int32 SafeCount() { }
	// RVA: 0x3f7f40c VA: 0x759659740c
	public Void UpdateMe() { }
	// RVA: 0x3f805b4 VA: 0x75965985b4
	public Void Clear() { }
	// RVA: 0x3f8065c VA: 0x759659865c
	public Void ExtendStackCnt(Int32 extend) { }
	// RVA: 0x3f8067c VA: 0x759659867c
	public Void SetMaxStackCnt(Int32 count) { }
	// RVA: 0x3f8011c VA: 0x759659811c
	private Boolean _DoAddInternal(Buff buff) { }
	// RVA: 0x3f80450 VA: 0x7596598450
	private Void _DoUpdateInternal() { }
}
```