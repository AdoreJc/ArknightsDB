# SelectTween

**Namespace:** ` `


## Fields

- `NameCardV2BaseRemovableModuleView m_view`

- `Single m_value`

- `Single m_cachedInNameCardHeight`

- `Boolean <isInNameCard>k__BackingField`


## Properties

- `Boolean isInNameCard`


## Methods

- `Boolean get_isInNameCard()`

- `Void set_isInNameCard(Boolean)`

- `Single _GetValue()`

- `Void _SetValue(Single)`

- `Void <>xLuaBaseProxy_ResetToState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SelectTween : UISwitchTween
{
	private NameCardV2BaseRemovableModuleView m_view; // 0x38
	private Single m_value; // 0x40
	private Single m_cachedInNameCardHeight; // 0x44
	private Boolean <isInNameCard>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_isInNameCard; // 0x0
	private static DelegateBridge __Hotfix0_set_isInNameCard; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_GenerateTweenOfHide; // 0x18
	private static DelegateBridge __Hotfix0_GenerateTweenOfShow; // 0x20
	private static DelegateBridge __Hotfix0_ResetToState; // 0x28
	private static DelegateBridge __Hotfix0__GetValue; // 0x30
	private static DelegateBridge __Hotfix0__SetValue; // 0x38

	private Boolean isInNameCard { get; set; }

	// RVA: 0x28e1c04 VA: 0x7594ef9c04
	private Boolean get_isInNameCard() { }
	// RVA: 0x28e19c4 VA: 0x7594ef99c4
	public Void set_isInNameCard(Boolean value) { }
	// RVA: 0x28e1af0 VA: 0x7594ef9af0
	public Void .ctor(NameCardV2BaseRemovableModuleView view) { }
	// RVA: 0x28e1c6c VA: 0x7594ef9c6c
	protected override ITweenHandler GenerateTweenOfHide() { }
	// RVA: 0x28e1e3c VA: 0x7594ef9e3c
	protected override ITweenHandler GenerateTweenOfShow() { }
	// RVA: 0x28e200c VA: 0x7594efa00c
	protected override Void ResetToState(Boolean isShow) { }
	// RVA: 0x28e21a4 VA: 0x7594efa1a4
	private Single _GetValue() { }
	// RVA: 0x28e2098 VA: 0x7594efa098
	private Void _SetValue(Single value) { }
	// RVA: 0x28e220c VA: 0x7594efa20c
	private Void <>xLuaBaseProxy_ResetToState(Boolean P0) { }
}
```