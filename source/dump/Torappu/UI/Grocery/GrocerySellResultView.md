# GrocerySellResultView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Image _goodIcon`

- `GrocerySellSpacingTextItem _totalIncomeText`

- `GrocerySellResultRankItem _rankItemPrefab`

- `TwoStateToggle _nextButtonToggle`

- `Text _sellGoodNameText`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInited`

- `GrocerySellResultTextTween m_incomeTween`

- `Int32 m_cachedTotalIncome`

- `Int32 m_cachedPlayerTotalIncome`


## Properties

- `Int32 ringCount`


## Methods

- `Int32 get_ringCount()`

- `Void OnNextClicked()`

- `Void PlayDiagramTweenWithIndex(Int32, Single)`

- `Void PlayTextTween(Single)`

- `IEnumerator ResetDiagramTweenAtBegin()`

- `IEnumerator ResetTextTweenAtBegin()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultView : DataBinder`1, IHotfixable
{
	private GameObject[] _sellStateIcons; // 0x20
	private Image _goodIcon; // 0x28
	private GrocerySellResultDiagramRingItem[] _rings; // 0x30
	private GrocerySellSpacingTextItem _totalIncomeText; // 0x38
	private GrocerySellResultRankItem _rankItemPrefab; // 0x40
	private Transform[] _rankItemParents; // 0x48
	private TwoStateToggle _nextButtonToggle; // 0x50
	private Text _sellGoodNameText; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private Boolean m_hasInited; // 0x70
	private List`1 m_rankItems; // 0x78
	private List`1 m_ringTweens; // 0x80
	private GrocerySellResultTextTween m_incomeTween; // 0x88
	private List`1 m_cachedSellInfo; // 0x90
	private Int32 m_cachedTotalIncome; // 0x98
	private Int32 m_cachedPlayerTotalIncome; // 0x9c
	private static DelegateBridge __Hotfix0_get_ringCount; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnNextClicked; // 0x10
	private static DelegateBridge __Hotfix0_PlayDiagramTweenWithIndex; // 0x18
	private static DelegateBridge __Hotfix0_PlayTextTween; // 0x20
	private static DelegateBridge __Hotfix0_ResetDiagramTweenAtBegin; // 0x28
	private static DelegateBridge __Hotfix0_ResetTextTweenAtBegin; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Int32 ringCount { get; }

	// RVA: 0x28a53b8 VA: 0x7594ebd3b8
	public Int32 get_ringCount() { }
	// RVA: 0x28a5ca8 VA: 0x7594ebdca8
	public override Void OnValueChanged(GrocerySellResultProperty property) { }
	// RVA: 0x28a6328 VA: 0x7594ebe328
	public Void OnNextClicked() { }
	// RVA: 0x28a5438 VA: 0x7594ebd438
	public Void PlayDiagramTweenWithIndex(Int32 index, Single duration) { }
	// RVA: 0x28a57d8 VA: 0x7594ebd7d8
	public Void PlayTextTween(Single duration) { }
	// RVA: 0x28a530c VA: 0x7594ebd30c
	public IEnumerator ResetDiagramTweenAtBegin() { }
	// RVA: 0x28a572c VA: 0x7594ebd72c
	public IEnumerator ResetTextTweenAtBegin() { }
	// RVA: 0x28a60b8 VA: 0x7594ebe0b8
	private Void _InitIfNot() { }
	// RVA: 0x28a641c VA: 0x7594ebe41c
	public Void .ctor() { }
}
```