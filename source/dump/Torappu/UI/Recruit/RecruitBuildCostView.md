# RecruitBuildCostView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `GameObject _costCardPrefab`

- `Transform _costCardContainer`

- `Boolean m_isInited`

- `RecruitBuildConfigCostCard m_itemGold`

- `RecruitBuildConfigCostCard m_itemRecruitLicense`


## Methods

- `Void _InitIfNot()`

- `Void Render(BuildSlotViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildCostView : MonoBehaviour
{
	private GameObject _costCardPrefab; // 0x18
	private Transform _costCardContainer; // 0x20
	public const Int32 MAX_COST_ITEM; // 0x0
	private Boolean m_isInited; // 0x28
	private RecruitBuildConfigCostCard m_itemGold; // 0x30
	private RecruitBuildConfigCostCard m_itemRecruitLicense; // 0x38
	private List`1 m_itemCardList; // 0x40


	// RVA: 0x2704810 VA: 0x7594d1c810
	private Void _InitIfNot() { }
	// RVA: 0x2704a24 VA: 0x7594d1ca24
	public Void Render(BuildSlotViewModel viewModel) { }
	// RVA: 0x2704c7c VA: 0x7594d1cc7c
	private static Void _UpdateItemCard(RecruitBuildConfigCostCard costCard, UIItemViewModel viewModel, Int64 curCount) { }
	// RVA: 0x2704cdc VA: 0x7594d1ccdc
	public Void .ctor() { }
}
```