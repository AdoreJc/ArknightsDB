# SettingButton

**Namespace:** `Torappu.UI.Setting`


## Fields

- `Button _button`

- `Animator _animator`

- `Boolean _reverse`

- `Boolean m_value`


## Methods

- `Void _OnClick()`

- `Void <>xLuaBaseProxy_RefreshState()`

- `Void <>xLuaBaseProxy_SetData(SettingType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Setting
public class SettingButton : SettingCommonObject
{
	private Button _button; // 0x30
	private Animator _animator; // 0x38
	private Boolean _reverse; // 0x40
	private Boolean m_value; // 0x41
	private static DelegateBridge __Hotfix0_RefreshState; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_SetCommonObjectEnabled; // 0x10
	private static DelegateBridge __Hotfix0__OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2479b34 VA: 0x7594a91b34
	protected override Void RefreshState() { }
	// RVA: 0x2479e08 VA: 0x7594a91e08
	protected override Void SetData(SettingType type) { }
	// RVA: 0x247a0c8 VA: 0x7594a920c8
	protected override Void SetCommonObjectEnabled(Boolean enabled) { }
	// RVA: 0x247a180 VA: 0x7594a92180
	private Void _OnClick() { }
	// RVA: 0x247a270 VA: 0x7594a92270
	public Void .ctor() { }
	// RVA: 0x247a354 VA: 0x7594a92354
	private Void <>xLuaBaseProxy_RefreshState() { }
	// RVA: 0x247a358 VA: 0x7594a92358
	private Void <>xLuaBaseProxy_SetData(SettingType P0) { }
}
```