# BlockerManager

**Namespace:** ` `


## Fields

- `Single m_lastIndex`

- `Boolean <isInertiaing>k__BackingField`


## Properties

- `Boolean isInertiaing`


## Methods

- `Boolean get_isInertiaing()`

- `Void set_isInertiaing(Boolean)`

- `Void Init(Int32, IList`1)`

- `Void StartInertia(Single)`

- `Boolean HitInertiaBlock(Single, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BlockerManager : IHotfixable
{
	private const Single INERTIA_BIAS; // 0x0
	private List`1 m_inertiaBlockers; // 0x10
	private Single m_lastIndex; // 0x18
	private Boolean <isInertiaing>k__BackingField; // 0x1c
	private static DelegateBridge __Hotfix0_get_isInertiaing; // 0x0
	private static DelegateBridge __Hotfix0_set_isInertiaing; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_StartInertia; // 0x18
	private static DelegateBridge __Hotfix0_HitInertiaBlock; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Boolean isInertiaing { get; set; }

	// RVA: 0x222191c VA: 0x759483991c
	public Boolean get_isInertiaing() { }
	// RVA: 0x2223048 VA: 0x759483b048
	private Void set_isInertiaing(Boolean value) { }
	// RVA: 0x22208c4 VA: 0x75948388c4
	public Void Init(Int32 pageCount, IList`1 blockFrames) { }
	// RVA: 0x2221984 VA: 0x7594839984
	public Void StartInertia(Single fromIndex) { }
	// RVA: 0x2221a0c VA: 0x7594839a0c
	public Boolean HitInertiaBlock(Single curIndex, out Single preferTo) { }
	// RVA: 0x2222348 VA: 0x759483a348
	public Void .ctor() { }
}
```