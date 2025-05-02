# Act1ArcadeSettlementCharCardView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeSettlementCharCardItemView _cardItemPrefab`

- `RectTransform _assistCardHolder`

- `Act1ArcadeSettlementCharCardItemView m_assistCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnRender(Act1ArcadeSettlementModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeSettlementCharCardView : MonoBehaviour, IHotfixable
{
	private Act1ArcadeSettlementCharCardItemView _cardItemPrefab; // 0x18
	private RectTransform[] _squadCardHolders; // 0x20
	private RectTransform _assistCardHolder; // 0x28
	private List`1 m_squadCards; // 0x30
	private Act1ArcadeSettlementCharCardItemView m_assistCard; // 0x38
	private Boolean m_isInited; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3408980 VA: 0x7595a20980
	private Void _InitIfNot() { }
	// RVA: 0x3408ba4 VA: 0x7595a20ba4
	public Void OnRender(Act1ArcadeSettlementModel settlementModel) { }
	// RVA: 0x3408d3c VA: 0x7595a20d3c
	public Void .ctor() { }
}
```