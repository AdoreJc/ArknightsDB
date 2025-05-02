# VoicelangSettingConfirmView

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `GameObject m_goTitleSingle`

- `GameObject m_goTitleBatch`

- `VoicelangTypeItemView m_prefabLangItem`

- `RectTransform m_langItemRoot`

- `Button m_btnConfirm`

- `Image m_bgConfirm`

- `GameObject m_goConfirmMask`

- `Color m_bgConfirmNormalColor`

- `Color m_bgConfirmDisableColor`

- `Text m_lbHint`

- `RectTransform m_rectTransRoot`

- `Single m_panelMoveDuration`

- `GameObject m_block`

- `UnityEvent m_onConfirm`

- `UnityEvent m_onCancel`

- `UISelectLangTypeEvent m_onSelectLangType`

- `ConfirmViewState m_lastState`

- `VoiceConfirmSwitchTween m_switchTween`

- `Boolean m_isInited`


## Methods

- `Void Render(VoicelangSettingConfirmViewModel)`

- `Void Init(UnityEvent, UnityEvent, UISelectLangTypeEvent)`

- `Void _OpenWithTween()`

- `Void _CloseWithTween()`

- `Void _OnInitTopMenu(GameObject)`

- `Void OnConfirm()`

- `Void OnCancel()`

- `Void <_OnInitTopMenu>b__25_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangSettingConfirmView : MonoBehaviour, IHotfixable
{
	private GameObject m_goTitleSingle; // 0x18
	private GameObject m_goTitleBatch; // 0x20
	private VoicelangTypeItemView m_prefabLangItem; // 0x28
	private RectTransform m_langItemRoot; // 0x30
	private Button m_btnConfirm; // 0x38
	private Image m_bgConfirm; // 0x40
	private GameObject m_goConfirmMask; // 0x48
	private Color m_bgConfirmNormalColor; // 0x50
	private Color m_bgConfirmDisableColor; // 0x60
	private Text m_lbHint; // 0x70
	private RectTransform m_rectTransRoot; // 0x78
	private Single m_panelMoveDuration; // 0x80
	private GameObject m_block; // 0x88
	private UnityEvent m_onConfirm; // 0x90
	private UnityEvent m_onCancel; // 0x98
	private List`1 m_itemList; // 0xa0
	private UISelectLangTypeEvent m_onSelectLangType; // 0xa8
	private ConfirmViewState m_lastState; // 0xb0
	private VoiceConfirmSwitchTween m_switchTween; // 0xb8
	private Boolean m_isInited; // 0xc0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__OpenWithTween; // 0x10
	private static DelegateBridge __Hotfix0__CloseWithTween; // 0x18
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x20
	private static DelegateBridge __Hotfix0__FilterDisplayLangType; // 0x28
	private static DelegateBridge __Hotfix0_OnConfirm; // 0x30
	private static DelegateBridge __Hotfix0_OnCancel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x229f9b0 VA: 0x75948b79b0
	public Void Render(VoicelangSettingConfirmViewModel model) { }
	// RVA: 0x229fde4 VA: 0x75948b7de4
	public Void Init(UnityEvent onConfirm, UnityEvent onCancel, UISelectLangTypeEvent onSelect) { }
	// RVA: 0x22a02fc VA: 0x75948b82fc
	private Void _OpenWithTween() { }
	// RVA: 0x22a0288 VA: 0x75948b8288
	private Void _CloseWithTween() { }
	// RVA: 0x22a0770 VA: 0x75948b8770
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x22a08b8 VA: 0x75948b88b8
	private static VoiceLangType _FilterDisplayLangType(VoiceLangType voiceLang) { }
	// RVA: 0x22a0954 VA: 0x75948b8954
	public Void OnConfirm() { }
	// RVA: 0x22a09d0 VA: 0x75948b89d0
	public Void OnCancel() { }
	// RVA: 0x22a0a4c VA: 0x75948b8a4c
	public Void .ctor() { }
	// RVA: 0x22a0abc VA: 0x75948b8abc
	private Void <_OnInitTopMenu>b__25_0() { }
}
```