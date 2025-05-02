# TuningPlayMenuView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductSlotGroupItemView _openOrcheBtnGroupItemView`

- `TuningProductSlotGroupItemView _closeOrcheBtnGroupItemView`

- `GameObject _hasNewProductTypeObj`

- `Text _productTypeText`

- `Transform _cardHolder`

- `TuningCommonCard _commonCardPrefab`

- `Single _cardScaler`

- `CanvasGroup _cardGroup`

- `Single _showAlpha`

- `Single _hideAlpha`

- `Single _cardTweenDuration`

- `UIStateFinder m_stateFinder`

- `TuningCommonCard m_commonCard`

- `Sequence m_cardSequence`

- `Int32 m_cachedCardChangeSequenceNum`


## Methods

- `Void _RenderCard(TuningPlayViewModel)`

- `Void OnClickOpenOrche()`

- `Void OnClickCloseOrche()`

- `Void OnClickTransToMusicHandbookState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningPlayMenuView : DataBinder`1
{
	private TuningProductSlotGroupItemView _openOrcheBtnGroupItemView; // 0x20
	private TuningProductSlotGroupItemView _closeOrcheBtnGroupItemView; // 0x28
	private GameObject _hasNewProductTypeObj; // 0x30
	private Text _productTypeText; // 0x38
	private Transform _cardHolder; // 0x40
	private TuningCommonCard _commonCardPrefab; // 0x48
	private Single _cardScaler; // 0x50
	private CanvasGroup _cardGroup; // 0x58
	private Single _showAlpha; // 0x60
	private Single _hideAlpha; // 0x64
	private Single _cardTweenDuration; // 0x68
	private UIStateFinder m_stateFinder; // 0x70
	private TuningCommonCard m_commonCard; // 0x80
	private Sequence m_cardSequence; // 0x88
	private Int32 m_cachedCardChangeSequenceNum; // 0x90
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderCard; // 0x8
	private static DelegateBridge __Hotfix0_OnClickOpenOrche; // 0x10
	private static DelegateBridge __Hotfix0_OnClickCloseOrche; // 0x18
	private static DelegateBridge __Hotfix0_OnClickTransToMusicHandbookState; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x232f118 VA: 0x7594947118
	public override Void OnValueChanged(TuningPlayProperty property) { }
	// RVA: 0x232f384 VA: 0x7594947384
	private Void _RenderCard(TuningPlayViewModel model) { }
	// RVA: 0x232f7e8 VA: 0x75949477e8
	public Void OnClickOpenOrche() { }
	// RVA: 0x232f88c VA: 0x759494788c
	public Void OnClickCloseOrche() { }
	// RVA: 0x232f930 VA: 0x7594947930
	public Void OnClickTransToMusicHandbookState() { }
	// RVA: 0x232f9d4 VA: 0x75949479d4
	public Void .ctor() { }
}
```