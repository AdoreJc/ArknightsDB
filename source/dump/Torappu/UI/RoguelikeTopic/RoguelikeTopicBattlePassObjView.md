# RoguelikeTopicBattlePassObjView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Text _num`

- `UIAtlasImage _valuableBkg`

- `UIAtlasImage _validLightImg`

- `UIAtlasImage _alreadyGotImg`

- `UIAtlasImage _lineLeft`

- `UIAtlasImage _lineRight`

- `UIAtlasImage _lineSpRight`

- `RectTransform _itemCardContainer`

- `Single _itemCardScale`

- `UIAtlasImage _normalDot`

- `UIAtlasImage _rareDot`

- `UIAtlasImage _valuableDot`

- `UIAtlasImage _availableDot`

- `GameObject _numPart`

- `GameObject _normalPart`

- `GameObject _futurePart`

- `GameObject _endPart`

- `Button _hotspotBtn`

- `CanvasGroup _itemCardCanvasGroup`

- `UIAtlasImage _imgValidNotice`

- `Text _textExpandCaption`

- `Text _validNoticeText`

- `GameObject _purchaseFirstLeftLine`

- `GameObject _purchaseFirstLeftRaycastReceiver`

- `GameObject _purchaseLastRightRaycastReceiver`

- `UIItemCard m_itemCard`

- `String m_cachedBpId`


## Methods

- `Void Render(RoguelikeTopicBPObjViewModel, Param)`

- `Void _DealWithPurchaseParts(RoguelikeTopicBPObjViewModel, Param)`

- `Void _OnItemClick(Int32)`

- `Void OnRewardClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassObjView : MonoBehaviour, IHotfixable
{
	private Text _num; // 0x18
	private UIAtlasImage _valuableBkg; // 0x20
	private UIAtlasImage _validLightImg; // 0x28
	private UIAtlasImage _alreadyGotImg; // 0x30
	private UIAtlasImage _lineLeft; // 0x38
	private UIAtlasImage _lineRight; // 0x40
	private UIAtlasImage _lineSpRight; // 0x48
	private RectTransform _itemCardContainer; // 0x50
	private Single _itemCardScale; // 0x58
	private UIAtlasImage _normalDot; // 0x60
	private UIAtlasImage _rareDot; // 0x68
	private UIAtlasImage _valuableDot; // 0x70
	private UIAtlasImage _availableDot; // 0x78
	private GameObject _numPart; // 0x80
	private GameObject _normalPart; // 0x88
	private GameObject _futurePart; // 0x90
	private GameObject _endPart; // 0x98
	private Button _hotspotBtn; // 0xa0
	private CanvasGroup _itemCardCanvasGroup; // 0xa8
	private UIAtlasImage _imgValidNotice; // 0xb0
	private Text _textExpandCaption; // 0xb8
	private Text _validNoticeText; // 0xc0
	private GameObject _purchaseFirstLeftLine; // 0xc8
	private GameObject _purchaseFirstLeftRaycastReceiver; // 0xd0
	private GameObject _purchaseLastRightRaycastReceiver; // 0xd8
	public Action`1 rewardClickAction; // 0xe0
	private UIItemCard m_itemCard; // 0xe8
	private String m_cachedBpId; // 0xf0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__DealWithPurchaseParts; // 0x8
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x10
	private static DelegateBridge __Hotfix0_OnRewardClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x263564c VA: 0x7594c4d64c
	public Void Render(RoguelikeTopicBPObjViewModel viewModel, Param param) { }
	// RVA: 0x263722c VA: 0x7594c4f22c
	private Void _DealWithPurchaseParts(RoguelikeTopicBPObjViewModel viewModel, Param param) { }
	// RVA: 0x2637328 VA: 0x7594c4f328
	private Void _OnItemClick(Int32 index) { }
	// RVA: 0x2637430 VA: 0x7594c4f430
	public Void OnRewardClick() { }
	// RVA: 0x26374c4 VA: 0x7594c4f4c4
	public Void .ctor() { }
}
```