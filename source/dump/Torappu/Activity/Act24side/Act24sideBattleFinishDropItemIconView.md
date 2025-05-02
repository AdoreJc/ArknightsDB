# Act24sideBattleFinishDropItemIconView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Transform _itemContainer`

- `Act24sideMeldingItemView _itemViewPrefab`

- `Animator m_animator`

- `Act24sideMeldingItemView m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `IEnumerator _RenderAfterTime(Single)`

- `Void Render(Act24sideBattleFinishMeldingDropItemViewModel, String, Single)`

- `Void _PlayItemDropSE()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleFinishDropItemIconView : MonoBehaviour, IHotfixable
{
	private Transform _itemContainer; // 0x18
	private Act24sideMeldingItemView _itemViewPrefab; // 0x20
	private Animator m_animator; // 0x28
	private Act24sideMeldingItemView m_itemCard; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__RenderAfterTime; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__PlayItemDropSE; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x328fb60 VA: 0x75958a7b60
	private Void _InitIfNot() { }
	// RVA: 0x328fca4 VA: 0x75958a7ca4
	private IEnumerator _RenderAfterTime(Single passTime) { }
	// RVA: 0x328fd90 VA: 0x75958a7d90
	public Void Render(Act24sideBattleFinishMeldingDropItemViewModel itemModel, String actId, Single passTime) { }
	// RVA: 0x328fe94 VA: 0x75958a7e94
	private Void _PlayItemDropSE() { }
	// RVA: 0x328ff3c VA: 0x75958a7f3c
	public Void .ctor() { }
}
```