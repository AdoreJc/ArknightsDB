# VoicelangSettingConfirmBinder

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `RectTransform m_panelRoot`

- `VoicelangSettingConfirmView m_prefab`

- `UnityEvent m_onConfirm`

- `UnityEvent m_onCancel`

- `UISelectLangTypeEvent m_onSelectLangType`

- `Boolean m_isInited`

- `VoicelangSettingConfirmView m_view`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangSettingConfirmBinder : DataBinder`1, IHotfixable
{
	private RectTransform m_panelRoot; // 0x20
	private VoicelangSettingConfirmView m_prefab; // 0x28
	private UnityEvent m_onConfirm; // 0x30
	private UnityEvent m_onCancel; // 0x38
	private UISelectLangTypeEvent m_onSelectLangType; // 0x40
	private Boolean m_isInited; // 0x48
	private VoicelangSettingConfirmView m_view; // 0x50
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x229f76c VA: 0x75948b776c
	public override Void OnValueChanged(VoicelangSettingConfirmViewProperty property) { }
	// RVA: 0x229f898 VA: 0x75948b7898
	private Void _InitIfNot() { }
	// RVA: 0x22a01f8 VA: 0x75948b81f8
	public Void .ctor() { }
}
```