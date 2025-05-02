# FloatController

**Namespace:** ` `


## Fields

- `RL02OuterBuffController m_closure`


## Methods

- `Void SetShowSummary(Boolean)`

- `Void _SetShowPanel(FloatType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FloatController : IHotfixable
{
	private RL02OuterBuffController m_closure; // 0x10
	private ListDict`2 m_floats; // 0x18
	private Nullable`1 m_hasPanelShown; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetShowSummary; // 0x8
	private static DelegateBridge __Hotfix0__SetShowPanel; // 0x10


	// RVA: 0x26bb44c VA: 0x7594cd344c
	public Void .ctor(RL02OuterBuffController closure) { }
	// RVA: 0x26bcb34 VA: 0x7594cd4b34
	public Void SetShowSummary(Boolean isShow) { }
	// RVA: 0x26bdfd8 VA: 0x7594cd5fd8
	private Void _SetShowPanel(FloatType type, Boolean isShow) { }
}
```