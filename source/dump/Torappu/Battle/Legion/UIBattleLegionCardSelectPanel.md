# UIBattleLegionCardSelectPanel

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `Text _txtTopTips`

- `UIAtlasImage _imgBgCenter`

- `CanvasGroup _canvasBgCenter`

- `Color _colorBgDiscard`

- `Color _colorBgSelect`

- `Color _colorBgPurple`

- `SimpleLayoutContent _cardList`

- `RectTransform _rectCancelBtn`

- `CanvasGroup _canvasCancelBtn`

- `ThreeStateToggle _confirmBtnToggle`

- `RectTransform _rectConfirmBtn`

- `RectTransform _rectConfirmDiscardBtn`

- `RectTransform _rectConfirmPurpleBtn`

- `CanvasGroup _canvasConfirmBtn`

- `Button _confirmBtn`

- `Button _confirmBtnRed`

- `Button _confirmBtnPurple`

- `Button _cancleBtn`

- `GameObject _objTrapDetail`

- `Transform _transTrapDetail`

- `Text _textTrapDetail`

- `CardListAdapter m_cardListAdapter`

- `CardSelectPanelShowTween m_CardSelectPanelShowTween`

- `LegionUICardSelectState m_legionState`

- `Boolean m_isSingleChoose`

- `Int32 m_canSelectNum`

- `Boolean m_hasInited`

- `CoroutineId m_coroutineEnterPanel`


## Methods

- `Void Show(LegionUICardSelectState)`

- `Void Hide()`

- `Void OnConfirmSelectClick()`

- `Void OnCancelSelectClick()`

- `Void OnDetailBgClick()`

- `Void _InitIfNot()`

- `Void _OnCancel()`

- `Void _ShowCancelTips()`

- `IEnumerator _PlayEnterPanelTween()`

- `Void _SetSelectTips(Boolean, Boolean, Int32, Boolean, LegionSelectCardType)`

- `Void _OnCardClick(UInt32)`

- `Void _OnShowTrapDetail(String, Single)`

- `Void _CalcSingleCardSelect(UInt32)`

- `Void _CalcMultiCardSelect(UInt32)`

- `CardModel _GetCardModel(UInt32)`

- `Void _UpdateSelectingCount(Int32)`

- `Void <_ShowCancelTips>b__42_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class UIBattleLegionCardSelectPanel : MonoBehaviour, IHotfixable
{
	private Text _txtTopTips; // 0x18
	private UIAtlasImage _imgBgCenter; // 0x20
	private CanvasGroup _canvasBgCenter; // 0x28
	private Color _colorBgDiscard; // 0x30
	private Color _colorBgSelect; // 0x40
	private Color _colorBgPurple; // 0x50
	private SimpleLayoutContent _cardList; // 0x60
	private RectTransform _rectCancelBtn; // 0x68
	private CanvasGroup _canvasCancelBtn; // 0x70
	private ThreeStateToggle _confirmBtnToggle; // 0x78
	private RectTransform _rectConfirmBtn; // 0x80
	private RectTransform _rectConfirmDiscardBtn; // 0x88
	private RectTransform _rectConfirmPurpleBtn; // 0x90
	private CanvasGroup _canvasConfirmBtn; // 0x98
	private Button _confirmBtn; // 0xa0
	private Button _confirmBtnRed; // 0xa8
	private Button _confirmBtnPurple; // 0xb0
	private Button _cancleBtn; // 0xb8
	private GameObject _objTrapDetail; // 0xc0
	private Transform _transTrapDetail; // 0xc8
	private Text _textTrapDetail; // 0xd0
	private List`1 m_cardList; // 0xd8
	private List`1 m_cardItemList; // 0xe0
	private CardListAdapter m_cardListAdapter; // 0xe8
	private CardSelectPanelShowTween m_CardSelectPanelShowTween; // 0xf0
	private LegionUICardSelectState m_legionState; // 0xf8
	private List`1 m_cardIdList; // 0x100
	private List`1 m_selectIdList; // 0x108
	private Boolean m_isSingleChoose; // 0x110
	private Int32 m_canSelectNum; // 0x114
	private Boolean m_hasInited; // 0x118
	private CoroutineId m_coroutineEnterPanel; // 0x120
	private const Single ENTER_TWEEN_DELAY; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_Hide; // 0x8
	private static DelegateBridge __Hotfix0_OnConfirmSelectClick; // 0x10
	private static DelegateBridge __Hotfix0_OnCancelSelectClick; // 0x18
	private static DelegateBridge __Hotfix0_OnDetailBgClick; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__OnCancel; // 0x30
	private static DelegateBridge __Hotfix0__ShowCancelTips; // 0x38
	private static DelegateBridge __Hotfix0__PlayEnterPanelTween; // 0x40
	private static DelegateBridge __Hotfix0__SetSelectTips; // 0x48
	private static DelegateBridge __Hotfix0__OnCardClick; // 0x50
	private static DelegateBridge __Hotfix0__OnShowTrapDetail; // 0x58
	private static DelegateBridge __Hotfix0__CalcSingleCardSelect; // 0x60
	private static DelegateBridge __Hotfix0__CalcMultiCardSelect; // 0x68
	private static DelegateBridge __Hotfix0__GetCardModel; // 0x70
	private static DelegateBridge __Hotfix0__UpdateSelectingCount; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x1db48f4 VA: 0x75943cc8f4
	public Void Show(LegionUICardSelectState legionState) { }
	// RVA: 0x1db59b4 VA: 0x75943cd9b4
	public Void Hide() { }
	// RVA: 0x1db5ac0 VA: 0x75943cdac0
	public Void OnConfirmSelectClick() { }
	// RVA: 0x1db5c78 VA: 0x75943cdc78
	public Void OnCancelSelectClick() { }
	// RVA: 0x1db5e9c VA: 0x75943cde9c
	public Void OnDetailBgClick() { }
	// RVA: 0x1db5120 VA: 0x75943cd120
	private Void _InitIfNot() { }
	// RVA: 0x1db6044 VA: 0x75943ce044
	private Void _OnCancel() { }
	// RVA: 0x1db5ce0 VA: 0x75943cdce0
	private Void _ShowCancelTips() { }
	// RVA: 0x1db5908 VA: 0x75943cd908
	private IEnumerator _PlayEnterPanelTween() { }
	// RVA: 0x1db56a8 VA: 0x75943cd6a8
	private Void _SetSelectTips(Boolean isAllTrapCard, Boolean isAllCharCard, Int32 canSelectNum, Boolean discard, LegionSelectCardType selectType) { }
	// RVA: 0x1db6188 VA: 0x75943ce188
	private Void _OnCardClick(UInt32 cardId) { }
	// RVA: 0x1db66dc VA: 0x75943ce6dc
	private Void _OnShowTrapDetail(String desc, Single posX) { }
	// RVA: 0x1db6284 VA: 0x75943ce284
	private Void _CalcSingleCardSelect(UInt32 cardId) { }
	// RVA: 0x1db6488 VA: 0x75943ce488
	private Void _CalcMultiCardSelect(UInt32 cardId) { }
	// RVA: 0x1db67b8 VA: 0x75943ce7b8
	private CardModel _GetCardModel(UInt32 cardId) { }
	// RVA: 0x1db68c4 VA: 0x75943ce8c4
	private Void _UpdateSelectingCount(Int32 selectingCount) { }
	// RVA: 0x1db69b4 VA: 0x75943ce9b4
	public Void .ctor() { }
	// RVA: 0x1db6b4c VA: 0x75943ceb4c
	private Void <_ShowCancelTips>b__42_0() { }
}
```