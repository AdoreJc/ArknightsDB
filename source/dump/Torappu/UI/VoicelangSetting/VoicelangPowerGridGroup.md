# VoicelangPowerGridGroup

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `UIRecycleLayoutGroup m_content`

- `VoicelangPowerItemView m_prefab`

- `UISelectPowerEvent m_onClick`

- `Image m_imgPower`

- `Text m_lbPower`

- `Sprite m_powerAllSprite`

- `Adapter m_adapter`


## Methods

- `Void _BuildVirtualViews(VoicelangPowerGroupViewModel)`

- `Void _UpdateView(VoicelangPowerGroupViewModel)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangPowerGridGroup : DataBinder`1
{
	private UIRecycleLayoutGroup m_content; // 0x20
	private VoicelangPowerItemView m_prefab; // 0x28
	private UISelectPowerEvent m_onClick; // 0x30
	private Image m_imgPower; // 0x38
	private Text m_lbPower; // 0x40
	private Sprite m_powerAllSprite; // 0x48
	private List`1 m_viewList; // 0x50
	private Adapter m_adapter; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__BuildVirtualViews; // 0x8
	private static DelegateBridge __Hotfix0__UpdateView; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x229d9d4 VA: 0x75948b59d4
	public override Void OnValueChanged(VoicelangPowerGroupViewProperty property) { }
	// RVA: 0x229dac4 VA: 0x75948b5ac4
	private Void _BuildVirtualViews(VoicelangPowerGroupViewModel viewModel) { }
	// RVA: 0x229dde0 VA: 0x75948b5de0
	private Void _UpdateView(VoicelangPowerGroupViewModel viewModel) { }
	// RVA: 0x229e650 VA: 0x75948b6650
	public Void Update() { }
	// RVA: 0x229e7b0 VA: 0x75948b67b0
	public Void .ctor() { }
}
```