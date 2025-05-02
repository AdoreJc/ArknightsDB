# RL03FocusForesightPlugin

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `GameObject _detailPart`

- `UIAtlasImage _atlasIcon`

- `UIAtlasObject _atlasObject`

- `GameObject _textPart`

- `Text _textDetail`

- `GameObject _listPart`

- `SimpleLayoutContent _itemContent`

- `Button _clickbutton`

- `GameObject _shiningLight`

- `CanvasGroup _attachDetailPanel`

- `GameObject _attachIcon`

- `SimpleLayoutContent _detailTextPart`

- `GameObject _totemMorePart`

- `RL03DetailItemView _itemView`

- `GameObject _totemButtonCont`

- `Action onClick`

- `Adapter m_adapter`

- `RL03TotemEffectAdapter m_descAdapter`

- `Boolean m_isInited`

- `FadeSwitchTween m_detailFade`

- `UIStateFinder m_finder`

- `RoguelikeRewardExtraInfoFactory m_foresightRewardExtraInfoFactory`


## Methods

- `Void _InitIfNot()`

- `Void _RenderHidePart(RoguelikeFocusViewModel)`

- `Void _RenderDetailPart(RoguelikeFocusViewModel)`

- `Void _RenderBattleDetailPart(RoguelikeFocusViewModel)`

- `Void _RenderShopOrGiftPart(String, List`1)`

- `Void _RenderText(String)`

- `Void OpenTotemDetail()`

- `Void CloseTotemDetail()`

- `Void _LoadRewardItemViewPluginIfNecessary(String)`

- `Void OpenItemForesightPlugin(String, List`1, String, Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03FocusForesightPlugin : RoguelikeFocusPlugin
{
	private GameObject _detailPart; // 0x28
	private UIAtlasImage _atlasIcon; // 0x30
	private UIAtlasObject _atlasObject; // 0x38
	private GameObject _textPart; // 0x40
	private Text _textDetail; // 0x48
	private GameObject _listPart; // 0x50
	private SimpleLayoutContent _itemContent; // 0x58
	private Button _clickbutton; // 0x60
	private GameObject _shiningLight; // 0x68
	private CanvasGroup _attachDetailPanel; // 0x70
	private GameObject _attachIcon; // 0x78
	private SimpleLayoutContent _detailTextPart; // 0x80
	private GameObject _totemMorePart; // 0x88
	private RL03DetailItemView _itemView; // 0x90
	private GameObject _totemButtonCont; // 0x98
	public Action onClick; // 0xa0
	private Adapter m_adapter; // 0xa8
	private RL03TotemEffectAdapter m_descAdapter; // 0xb0
	private Boolean m_isInited; // 0xb8
	private FadeSwitchTween m_detailFade; // 0xc0
	private UIStateFinder m_finder; // 0xc8
	private RoguelikeRewardExtraInfoFactory m_foresightRewardExtraInfoFactory; // 0xd8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderHidePart; // 0x10
	private static DelegateBridge __Hotfix0__RenderDetailPart; // 0x18
	private static DelegateBridge __Hotfix0__RenderBattleDetailPart; // 0x20
	private static DelegateBridge __Hotfix0__RenderShopOrGiftPart; // 0x28
	private static DelegateBridge __Hotfix0__RenderText; // 0x30
	private static DelegateBridge __Hotfix0_OpenTotemDetail; // 0x38
	private static DelegateBridge __Hotfix0_CloseTotemDetail; // 0x40
	private static DelegateBridge __Hotfix0__LoadRewardItemViewPluginIfNecessary; // 0x48
	private static DelegateBridge __Hotfix0_OpenItemForesightPlugin; // 0x50
	private static DelegateBridge __Hotfix0_OnClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2b8ba94 VA: 0x75951a3a94
	private Void _InitIfNot() { }
	// RVA: 0x2b8bcec VA: 0x75951a3cec
	public override Boolean Render(RoguelikeFocusViewModel viewModel) { }
	// RVA: 0x2b8c0a0 VA: 0x75951a40a0
	private Void _RenderHidePart(RoguelikeFocusViewModel viewModel) { }
	// RVA: 0x2b8c3e4 VA: 0x75951a43e4
	private Void _RenderDetailPart(RoguelikeFocusViewModel viewModel) { }
	// RVA: 0x2b8c6d0 VA: 0x75951a46d0
	private Void _RenderBattleDetailPart(RoguelikeFocusViewModel viewModel) { }
	// RVA: 0x2b8c998 VA: 0x75951a4998
	private Void _RenderShopOrGiftPart(String topicId, List`1 itemList) { }
	// RVA: 0x2b8cb40 VA: 0x75951a4b40
	private Void _RenderText(String detailText) { }
	// RVA: 0x2b8cc4c VA: 0x75951a4c4c
	public Void OpenTotemDetail() { }
	// RVA: 0x2b8cccc VA: 0x75951a4ccc
	public Void CloseTotemDetail() { }
	// RVA: 0x2b8cd4c VA: 0x75951a4d4c
	private Void _LoadRewardItemViewPluginIfNecessary(String topicId) { }
	// RVA: 0x2b8cee8 VA: 0x75951a4ee8
	public Void OpenItemForesightPlugin(String topicId, List`1 totemList, String paramText, Boolean showOr) { }
	// RVA: 0x2b8d2bc VA: 0x75951a52bc
	public Void OnClick() { }
	// RVA: 0x2b8d340 VA: 0x75951a5340
	public Void .ctor() { }
}
```