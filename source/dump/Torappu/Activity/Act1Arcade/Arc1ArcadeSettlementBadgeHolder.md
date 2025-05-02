# Arc1ArcadeSettlementBadgeHolder

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `RectTransform _holder`

- `Single _itemBasicWidth`

- `Act1ArcadeSettlementBadgeItemView _badgeItemViewPrefab`


## Methods

- `Void OnRender(Act1ArcadeSettlementModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Arc1ArcadeSettlementBadgeHolder : MonoBehaviour, IHotfixable
{
	private const Single START_ANIM_DELAY; // 0x0
	private const Single PER_LEVEL_ANIM_DELAY; // 0x0
	private RectTransform _holder; // 0x18
	private Single _itemBasicWidth; // 0x20
	private Act1ArcadeSettlementBadgeItemView _badgeItemViewPrefab; // 0x28
	private List`1 m_badgeViews; // 0x30
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x34076f0 VA: 0x7595a1f6f0
	public Void OnRender(Act1ArcadeSettlementModel settlementModel) { }
	// RVA: 0x3407bb4 VA: 0x7595a1fbb4
	public Void .ctor() { }
}
```