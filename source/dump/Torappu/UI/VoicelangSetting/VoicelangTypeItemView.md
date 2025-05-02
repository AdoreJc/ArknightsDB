# VoicelangTypeItemView

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `Text lb_langType`

- `GameObject go_new`

- `GameObject go_selected`

- `GameObject goInvalid`

- `Color color_valid`

- `Color color_invalid`

- `Animation anim_voice`

- `Image img_voice`

- `VoiceLangType m_type`

- `UISelectLangTypeEvent m_onSelctLangType`

- `VoicelangSettingConfirmViewModel m_model`

- `Boolean m_lastSelected`

- `String m_lastCharId`


## Methods

- `Void Render(VoicelangSettingConfirmViewModel)`

- `Void Init(VoiceLangType, UISelectLangTypeEvent)`

- `Void _TryPlayVoice(Boolean, VoicelangCardViewModel)`

- `Void Select()`

- `Void CancelSelect()`

- `Void StopAnim()`

- `Void PlayAnim()`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangTypeItemView : MonoBehaviour, IHotfixable
{
	private Text lb_langType; // 0x18
	private GameObject go_new; // 0x20
	private GameObject go_selected; // 0x28
	private GameObject goInvalid; // 0x30
	private Color color_valid; // 0x38
	private Color color_invalid; // 0x48
	private Animation anim_voice; // 0x58
	private Image img_voice; // 0x60
	private VoiceLangType m_type; // 0x68
	private UISelectLangTypeEvent m_onSelctLangType; // 0x70
	private VoicelangSettingConfirmViewModel m_model; // 0x78
	private Boolean m_lastSelected; // 0x80
	private String m_lastCharId; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__TryPlayVoice; // 0x10
	private static DelegateBridge __Hotfix0_Select; // 0x18
	private static DelegateBridge __Hotfix0_CancelSelect; // 0x20
	private static DelegateBridge __Hotfix0_StopAnim; // 0x28
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x30
	private static DelegateBridge __Hotfix0_OnClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x22a0370 VA: 0x75948b8370
	public Void Render(VoicelangSettingConfirmViewModel model) { }
	// RVA: 0x22a05ec VA: 0x75948b85ec
	public Void Init(VoiceLangType type, UISelectLangTypeEvent listener) { }
	// RVA: 0x22a0f58 VA: 0x75948b8f58
	private Void _TryPlayVoice(Boolean isSelect, VoicelangCardViewModel singleSelectChar) { }
	// RVA: 0x22a1204 VA: 0x75948b9204
	private Void Select() { }
	// RVA: 0x22a1444 VA: 0x75948b9444
	public Void CancelSelect() { }
	// RVA: 0x22a0ed0 VA: 0x75948b8ed0
	private Void StopAnim() { }
	// RVA: 0x22a117c VA: 0x75948b917c
	private Void PlayAnim() { }
	// RVA: 0x22a14b8 VA: 0x75948b94b8
	public Void OnClick() { }
	// RVA: 0x22a15c4 VA: 0x75948b95c4
	public Void .ctor() { }
}
```