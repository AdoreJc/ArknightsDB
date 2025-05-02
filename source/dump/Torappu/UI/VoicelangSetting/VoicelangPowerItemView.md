# VoicelangPowerItemView

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `Single m_selected_Height`

- `Single m_unSelected_Height`

- `Text m_lbPowerName`

- `Text m_lbPowerCode`

- `Image m_imgSelectedLogo`

- `Image m_imgUnselectedLogo`

- `GameObject m_go_Selected`

- `GameObject m_go_unSelected`

- `RectTransform rectTrans`

- `Sprite m_powerAllSprite`

- `GameObject m_go_New`

- `Boolean m_selected`

- `VoicelangPowerViewModel m_powerData`

- `UISelectPowerEvent m_onClick`


## Methods

- `Void SetPower(VoicelangPowerViewModel)`

- `Void SetSelected(Boolean)`

- `Void SetEvent(UISelectPowerEvent)`

- `Void OnButtonClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangPowerItemView : MonoBehaviour, IHotfixable
{
	private Single m_selected_Height; // 0x18
	private Single m_unSelected_Height; // 0x1c
	private Text m_lbPowerName; // 0x20
	private Text m_lbPowerCode; // 0x28
	private Image m_imgSelectedLogo; // 0x30
	private Image m_imgUnselectedLogo; // 0x38
	private GameObject m_go_Selected; // 0x40
	private GameObject m_go_unSelected; // 0x48
	private RectTransform rectTrans; // 0x50
	private Sprite m_powerAllSprite; // 0x58
	private GameObject m_go_New; // 0x60
	private Boolean m_selected; // 0x68
	private VoicelangPowerViewModel m_powerData; // 0x70
	private UISelectPowerEvent m_onClick; // 0x78
	private Int32[] m_fontSizes; // 0x80
	private static DelegateBridge __Hotfix0_SetPower; // 0x0
	private static DelegateBridge __Hotfix0_SetSelected; // 0x8
	private static DelegateBridge __Hotfix0_SetEvent; // 0x10
	private static DelegateBridge __Hotfix0_OnButtonClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x229e908 VA: 0x75948b6908
	public Void SetPower(VoicelangPowerViewModel powerData) { }
	// RVA: 0x229ea58 VA: 0x75948b6a58
	public Void SetSelected(Boolean selected) { }
	// RVA: 0x229ebb4 VA: 0x75948b6bb4
	public Void SetEvent(UISelectPowerEvent onClick) { }
	// RVA: 0x229ec38 VA: 0x75948b6c38
	public Void OnButtonClick() { }
	// RVA: 0x229ecdc VA: 0x75948b6cdc
	public Void .ctor() { }
}
```