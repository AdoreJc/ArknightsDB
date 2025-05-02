# SandboxV2ConfirmDialogView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Text _txtTitle`

- `Text _txtDesc`

- `Text _txtConfirm`

- `Text _txtCancel`

- `Image _imgIcon`

- `GameObject _panelThemeLight`

- `GameObject _panelThemeDark`

- `Graphic _graphicConfirmBg`

- `RectTransform _decoContainer`

- `RectTransform _backRt`

- `Boolean m_isInited`

- `Assets m_assetLoader`

- `SandboxV2ConfirmDialogConfirmAudioType m_cachedAudioType`

- `Action <onCancelClicked>k__BackingField`

- `Action <onConfirmClicked>k__BackingField`

- `Action <onBackPressed>k__BackingField`


## Properties

- `Action onCancelClicked`

- `Action onConfirmClicked`

- `Action onBackPressed`


## Methods

- `Action get_onCancelClicked()`

- `Void set_onCancelClicked(Action)`

- `Action get_onConfirmClicked()`

- `Void set_onConfirmClicked(Action)`

- `Action get_onBackPressed()`

- `Void set_onBackPressed(Action)`

- `Void Render(RenderParam)`

- `Void OnCancelBtnClicked()`

- `Void OnConfirmBtnClicked()`

- `Void OnBackPressed()`

- `Void _InitIfNot()`

- `Void _RenderThemeStyle(SandboxV2ConfirmDialogThemeType)`

- `Void _RenderConfirmStyle(SandboxV2ConfirmDialogConfirmVisualType)`

- `Void _RenderIcon(String, Sprite, Assets)`

- `Void _SetColorForGraphicItems(Graphic[], Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ConfirmDialogView : MonoBehaviour, IHotfixable
{
	private static Color LIGHT_TITLE_COLOR; // 0x0
	private static Color LIGHT_DESC_COLOR; // 0x10
	private static Color DARK_TITLE_COLOR; // 0x20
	private static Color DARK_DESC_COLOR; // 0x30
	private static Color GREEN_CONFIRM_BG_COLOR; // 0x40
	private static Color GREEN_CONFIRM_ITEMS_COLOR; // 0x50
	private static Color RED_CONFIRM_BG_COLOR; // 0x60
	private static Color RED_CONFIRM_ITEMS_COLOR; // 0x70
	private static Color GRAY_CONFIRM_BG_COLOR; // 0x80
	private static Color GRAY_CONFIRM_ITEMS_COLOR; // 0x90
	private static Color BLUE_CONFIRM_BG_COLOR; // 0xa0
	private static Color BLUE_CONFIRM_ITEMS_COLOR; // 0xb0
	private Text _txtTitle; // 0x18
	private Text _txtDesc; // 0x20
	private Text _txtConfirm; // 0x28
	private Text _txtCancel; // 0x30
	private Image _imgIcon; // 0x38
	private GameObject _panelThemeLight; // 0x40
	private GameObject _panelThemeDark; // 0x48
	private Graphic _graphicConfirmBg; // 0x50
	private Graphic[] _graphicConfirmItems; // 0x58
	private RectTransform _decoContainer; // 0x60
	private RectTransform _backRt; // 0x68
	private Boolean m_isInited; // 0x70
	private Assets m_assetLoader; // 0x78
	private SandboxV2ConfirmDialogConfirmAudioType m_cachedAudioType; // 0x80
	private Action <onCancelClicked>k__BackingField; // 0x88
	private Action <onConfirmClicked>k__BackingField; // 0x90
	private Action <onBackPressed>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_onCancelClicked; // 0xc0
	private static DelegateBridge __Hotfix0_set_onCancelClicked; // 0xc8
	private static DelegateBridge __Hotfix0_get_onConfirmClicked; // 0xd0
	private static DelegateBridge __Hotfix0_set_onConfirmClicked; // 0xd8
	private static DelegateBridge __Hotfix0_get_onBackPressed; // 0xe0
	private static DelegateBridge __Hotfix0_set_onBackPressed; // 0xe8
	private static DelegateBridge __Hotfix0_Render; // 0xf0
	private static DelegateBridge __Hotfix0_OnCancelBtnClicked; // 0xf8
	private static DelegateBridge __Hotfix0_OnConfirmBtnClicked; // 0x100
	private static DelegateBridge __Hotfix0_OnBackPressed; // 0x108
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x110
	private static DelegateBridge __Hotfix0__RenderThemeStyle; // 0x118
	private static DelegateBridge __Hotfix0__RenderConfirmStyle; // 0x120
	private static DelegateBridge __Hotfix0__RenderIcon; // 0x128
	private static DelegateBridge __Hotfix0__SetColorForGraphicItems; // 0x130
	private static DelegateBridge _c__Hotfix0_ctor; // 0x138

	private Action onCancelClicked { get; set; }
	private Action onConfirmClicked { get; set; }
	private Action onBackPressed { get; set; }

	// RVA: 0x25040f0 VA: 0x7594b1c0f0
	private Action get_onCancelClicked() { }
	// RVA: 0x25037ec VA: 0x7594b1b7ec
	public Void set_onCancelClicked(Action value) { }
	// RVA: 0x2504168 VA: 0x7594b1c168
	private Action get_onConfirmClicked() { }
	// RVA: 0x2503880 VA: 0x7594b1b880
	public Void set_onConfirmClicked(Action value) { }
	// RVA: 0x25041e0 VA: 0x7594b1c1e0
	private Action get_onBackPressed() { }
	// RVA: 0x2503914 VA: 0x7594b1b914
	public Void set_onBackPressed(Action value) { }
	// RVA: 0x2503a84 VA: 0x7594b1ba84
	public Void Render(RenderParam renderParam) { }
	// RVA: 0x25049c4 VA: 0x7594b1c9c4
	public Void OnCancelBtnClicked() { }
	// RVA: 0x2504a70 VA: 0x7594b1ca70
	public Void OnConfirmBtnClicked() { }
	// RVA: 0x2504be4 VA: 0x7594b1cbe4
	public Void OnBackPressed() { }
	// RVA: 0x2504258 VA: 0x7594b1c258
	private Void _InitIfNot() { }
	// RVA: 0x2504410 VA: 0x7594b1c410
	private Void _RenderThemeStyle(SandboxV2ConfirmDialogThemeType themeType) { }
	// RVA: 0x25045b8 VA: 0x7594b1c5b8
	private Void _RenderConfirmStyle(SandboxV2ConfirmDialogConfirmVisualType confirmVisualType) { }
	// RVA: 0x25047a0 VA: 0x7594b1c7a0
	private Void _RenderIcon(String iconId, Sprite iconSprite, Assets assetLoader) { }
	// RVA: 0x2504c90 VA: 0x7594b1cc90
	private Void _SetColorForGraphicItems(Graphic[] graphics, Color color) { }
	// RVA: 0x2504dd4 VA: 0x7594b1cdd4
	public Void .ctor() { }
	// RVA: 0x2504e54 VA: 0x7594b1ce54
	private static Void .cctor() { }
}
```