# SettingTabs

**Namespace:** `Torappu.UI.Setting`


## Fields

- `SettingTab _prefab`

- `Single _offset`

- `Int32 m_value`


## Methods

- `Void _OnValueChanged(Int32)`

- `Void <>xLuaBaseProxy_RefreshState()`

- `Void <>xLuaBaseProxy_SetData(SettingType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Setting
public class SettingTabs : SettingCommonObject
{
	private SettingTab _prefab; // 0x30
	private String[] _texts; // 0x38
	private Single _offset; // 0x40
	private SettingTab[] m_tabs; // 0x48
	private Int32 m_value; // 0x50
	private static DelegateBridge __Hotfix0_RefreshState; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_SetCommonObjectEnabled; // 0x10
	private static DelegateBridge __Hotfix0__OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x247b540 VA: 0x7594a93540
	protected override Void RefreshState() { }
	// RVA: 0x247b808 VA: 0x7594a93808
	protected override Void SetData(SettingType type) { }
	// RVA: 0x247b964 VA: 0x7594a93964
	protected override Void SetCommonObjectEnabled(Boolean enabled) { }
	// RVA: 0x247ba28 VA: 0x7594a93a28
	private Void _OnValueChanged(Int32 settingValue) { }
	// RVA: 0x247bb78 VA: 0x7594a93b78
	public Void .ctor() { }
	// RVA: 0x247bbe4 VA: 0x7594a93be4
	private Void <>xLuaBaseProxy_RefreshState() { }
	// RVA: 0x247bbe8 VA: 0x7594a93be8
	private Void <>xLuaBaseProxy_SetData(SettingType P0) { }
}
```