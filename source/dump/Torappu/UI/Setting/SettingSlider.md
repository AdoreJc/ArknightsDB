# SettingSlider

**Namespace:** `Torappu.UI.Setting`


## Fields

- `Single value`

- `Single _dataMax`

- `Text _valueText`

- `Slider _slider`

- `Int32 m_valueToInt`

- `Boolean m_initFlag`


## Methods

- `Void _OnValueChanged(Single)`

- `Void <>xLuaBaseProxy_RefreshState()`

- `Void <>xLuaBaseProxy_SetData(SettingType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Setting
public class SettingSlider : SettingCommonObject
{
	private Single value; // 0x30
	private Single _dataMax; // 0x34
	private Text _valueText; // 0x38
	private Slider _slider; // 0x40
	private Int32 m_valueToInt; // 0x48
	private Boolean m_initFlag; // 0x4c
	private static DelegateBridge __Hotfix0_RefreshState; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_SetCommonObjectEnabled; // 0x10
	private static DelegateBridge __Hotfix0__OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x247aa10 VA: 0x7594a92a10
	protected override Void RefreshState() { }
	// RVA: 0x247ab10 VA: 0x7594a92b10
	protected override Void SetData(SettingType type) { }
	// RVA: 0x247adf4 VA: 0x7594a92df4
	protected override Void SetCommonObjectEnabled(Boolean enabled) { }
	// RVA: 0x247ae78 VA: 0x7594a92e78
	private Void _OnValueChanged(Single settingValue) { }
	// RVA: 0x247b0e0 VA: 0x7594a930e0
	public Void .ctor() { }
	// RVA: 0x247b154 VA: 0x7594a93154
	private Void <>xLuaBaseProxy_RefreshState() { }
	// RVA: 0x247b158 VA: 0x7594a93158
	private Void <>xLuaBaseProxy_SetData(SettingType P0) { }
}
```