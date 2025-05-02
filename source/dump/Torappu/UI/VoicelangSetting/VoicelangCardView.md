# VoicelangCardView

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `Text lb_name`

- `UIAtlasImage image_ChrPortrait`

- `GameObject go_HightLight`

- `GameObject go_selectMask`

- `GameObject go_New`

- `Text lb_langTypeName`

- `GameObject go_undownloadMask`

- `GameObject go_voiceMark`

- `Text lb_lackVoice`

- `UISelectCardEvent m_onClick`

- `String m_portraitCache`

- `VoicelangCardViewModel m_viewModel`


## Methods

- `Void RenderCard(VoicelangCardViewModel)`

- `Void SetListenerIfNot(UISelectCardEvent)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangCardView : MonoBehaviour, IHotfixable
{
	private Text lb_name; // 0x18
	private UIAtlasImage image_ChrPortrait; // 0x20
	private GameObject go_HightLight; // 0x28
	private GameObject go_selectMask; // 0x30
	private GameObject go_New; // 0x38
	private Text lb_langTypeName; // 0x40
	private GameObject go_undownloadMask; // 0x48
	private GameObject go_voiceMark; // 0x50
	private Text lb_lackVoice; // 0x58
	private UISelectCardEvent m_onClick; // 0x60
	private String m_portraitCache; // 0x68
	private VoicelangCardViewModel m_viewModel; // 0x70
	private static DelegateBridge __Hotfix0_RenderCard; // 0x0
	private static DelegateBridge __Hotfix0_SetListenerIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x229d230 VA: 0x75948b5230
	public Void RenderCard(VoicelangCardViewModel viewModel) { }
	// RVA: 0x229d194 VA: 0x75948b5194
	public Void SetListenerIfNot(UISelectCardEvent listener) { }
	// RVA: 0x229d8a4 VA: 0x75948b58a4
	public Void OnClick() { }
	// RVA: 0x229d964 VA: 0x75948b5964
	public Void .ctor() { }
}
```