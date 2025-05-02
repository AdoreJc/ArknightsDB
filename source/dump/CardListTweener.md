# CardListTweener

**Namespace:** ` `


## Fields

- `UICardList m_cardList`

- `Vector2 m_sizeRange`

- `Int32 m_focusIndex`

- `Boolean m_tweening`

- `Single m_cachedTotalSize`


## Methods

- `Void OnUpdate()`

- `Void OnPossibleTotalSizeChange()`

- `Boolean TryRefreshCards(Int32, Boolean, Boolean)`

- `Void _CalculateTargetSizes(Int32)`

- `Boolean _CheckUnchanged()`

- `Void _DoApplyChanges(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CardListTweener
{
	private const Single TWEEN_STOP_EPS; // 0x0
	private const Single TWEEN_FRAME_STEP; // 0x0
	private UICardList m_cardList; // 0x10
	private Vector2 m_sizeRange; // 0x18
	private Int32 m_focusIndex; // 0x20
	private List`1 m_curSizes; // 0x28
	private List`1 m_targetSizes; // 0x30
	private Boolean m_tweening; // 0x38
	private Single m_cachedTotalSize; // 0x3c

	protected List`1 cards { get; }

	// RVA: 0x2031ff0 VA: 0x7594649ff0
	protected List`1 get_cards() { }
	// RVA: 0x2031484 VA: 0x7594649484
	public Void .ctor(UICardList cardList, Vector2 sizeRange) { }
	// RVA: 0x202fd18 VA: 0x7594647d18
	public Void OnUpdate() { }
	// RVA: 0x2030e40 VA: 0x7594648e40
	public Void OnPossibleTotalSizeChange() { }
	// RVA: 0x20308c0 VA: 0x75946488c0
	public Boolean TryRefreshCards(Int32 focusIndex, Boolean forceRebuild, Boolean isRefreshList) { }
	// RVA: 0x2032264 VA: 0x759464a264
	private Void _CalculateTargetSizes(Int32 cardCnt) { }
	// RVA: 0x20327b0 VA: 0x759464a7b0
	private Boolean _CheckUnchanged() { }
	// RVA: 0x203200c VA: 0x759464a00c
	private Void _DoApplyChanges(Boolean isRefreshList) { }
}
```