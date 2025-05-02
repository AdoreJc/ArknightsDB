# CrisisV2MapTreasureNodeView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `GameObject _unavailBgGo`

- `GameObject _availBgGo`

- `UIAtlasImage _imgRewardGlow`

- `Color _colorRewardGlowUnavail`

- `Color _colorRewardGlowAvail`

- `UIAtlasImage _imgRewardCaption`

- `Color _colorRewardCaptionUnavail`

- `Color _colorRewardCaptionAvail`

- `RectTransform _itemCardContainer`

- `Single _itemScale`

- `GameObject _iconIncompletedGo`

- `GameObject _iconAvailGo`

- `GameObject _iconClaimedGo`

- `CanvasGroup _nodeCanvasGroup`

- `Single _claimedAlpha`

- `GameObject _claimedMaskGo`

- `Text _textCurrent`

- `Text _textTotal`

- `GameObject _incompleteCaptionGo`

- `GameObject _completedCaptionGo`

- `GameObject _availCaptionGo`

- `GameObject _btnSkinPreviewGo`

- `UIItemCard m_itemCard`

- `UIItemViewModel m_itemViewModel`


## Methods

- `Void _RenderItemCard(CrisisV2MapTreasureNodeModel)`

- `Void EventBtnSkinPreview()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapTreasureNodeView : CrisisV2MapNodeViewBase
{
	private GameObject _unavailBgGo; // 0x50
	private GameObject _availBgGo; // 0x58
	private UIAtlasImage _imgRewardGlow; // 0x60
	private Color _colorRewardGlowUnavail; // 0x68
	private Color _colorRewardGlowAvail; // 0x78
	private UIAtlasImage _imgRewardCaption; // 0x88
	private Color _colorRewardCaptionUnavail; // 0x90
	private Color _colorRewardCaptionAvail; // 0xa0
	private RectTransform _itemCardContainer; // 0xb0
	private Single _itemScale; // 0xb8
	private GameObject _iconIncompletedGo; // 0xc0
	private GameObject _iconAvailGo; // 0xc8
	private GameObject _iconClaimedGo; // 0xd0
	private CanvasGroup _nodeCanvasGroup; // 0xd8
	private Single _claimedAlpha; // 0xe0
	private GameObject _claimedMaskGo; // 0xe8
	private Text _textCurrent; // 0xf0
	private Text _textTotal; // 0xf8
	private GameObject _incompleteCaptionGo; // 0x100
	private GameObject _completedCaptionGo; // 0x108
	private GameObject _availCaptionGo; // 0x110
	private GameObject _btnSkinPreviewGo; // 0x118
	private UIItemCard m_itemCard; // 0x120
	private UIItemViewModel m_itemViewModel; // 0x128
	private static DelegateBridge __Hotfix0_GetSlotType; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__RenderItemCard; // 0x10
	private static DelegateBridge __Hotfix0_EventBtnSkinPreview; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2c0c610 VA: 0x7595224610
	public override CrisisV2NodeSlotType GetSlotType() { }
	// RVA: 0x2c0c678 VA: 0x7595224678
	protected override Void Render() { }
	// RVA: 0x2c0cae8 VA: 0x7595224ae8
	private Void _RenderItemCard(CrisisV2MapTreasureNodeModel treasureModel) { }
	// RVA: 0x2c0cd08 VA: 0x7595224d08
	public Void EventBtnSkinPreview() { }
	// RVA: 0x2c0ce0c VA: 0x7595224e0c
	public Void .ctor() { }
}
```