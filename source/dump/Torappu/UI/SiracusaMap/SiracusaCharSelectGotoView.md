# SiracusaCharSelectGotoView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `UIAtlasImage _imgCharIcon`

- `UIAtlasImage _imgMissionIcon`

- `UIAtlasImage _imgBgTheme`

- `Text _textDialogue`

- `Text _txtCharName`

- `RectTransform _transAvgContainer`

- `UIAVGCharacter _uiAVGCharacter`

- `AnimationWrapper _enterAnimWrapper`

- `Text _txtCloseTip`

- `String m_cachedCharId`

- `Boolean m_hasInited`

- `Vector2 m_defaultAvgContainerPos`


## Methods

- `Void _PlayEntryAnim()`

- `Void _InitIfNot()`

- `Void _Render(SiracusaCharCardModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharSelectGotoView : DataBinder`1
{
	private UIAtlasImage _imgCharIcon; // 0x20
	private UIAtlasImage _imgMissionIcon; // 0x28
	private UIAtlasImage _imgBgTheme; // 0x30
	private Text _textDialogue; // 0x38
	private Text _txtCharName; // 0x40
	private RectTransform _transAvgContainer; // 0x48
	private UIAVGCharacter _uiAVGCharacter; // 0x50
	private AnimationWrapper _enterAnimWrapper; // 0x58
	private Text _txtCloseTip; // 0x60
	private String m_cachedCharId; // 0x68
	private Boolean m_hasInited; // 0x70
	private Vector2 m_defaultAvgContainerPos; // 0x74
	private const String ANIM_NAME; // 0x0
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x23ed738 VA: 0x7594a05738
	private Void _PlayEntryAnim() { }
	// RVA: 0x23ed7f0 VA: 0x7594a057f0
	private Void _InitIfNot() { }
	// RVA: 0x23ed8d0 VA: 0x7594a058d0
	private Void _Render(SiracusaCharCardModel viewModel) { }
	// RVA: 0x23edb30 VA: 0x7594a05b30
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x23edbf8 VA: 0x7594a05bf8
	public Void .ctor() { }
}
```