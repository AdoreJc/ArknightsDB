# RecruitBuildConfigCostView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `GameObject _costCardPrefab`

- `Transform _costCardContainer`

- `GameObject _specialTag`

- `Text _specialTagText`

- `Boolean m_isInited`

- `RecruitBuildConfigCostCard m_itemGold`

- `RecruitBuildConfigCostCard m_itemRecruitLicense`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildConfigCostView : DataBinder`1
{
	private GameObject _costCardPrefab; // 0x20
	private Transform _costCardContainer; // 0x28
	private GameObject _specialTag; // 0x30
	private Text _specialTagText; // 0x38
	public const Int32 MAX_COST_ITEM; // 0x0
	private Boolean m_isInited; // 0x40
	private RecruitBuildConfigCostCard m_itemGold; // 0x48
	private RecruitBuildConfigCostCard m_itemRecruitLicense; // 0x50
	private List`1 m_itemCardList; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__UpdateItemCard; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x270c9cc VA: 0x7594d249cc
	private Void _InitIfNot() { }
	// RVA: 0x270cc24 VA: 0x7594d24c24
	public override Void OnValueChanged(BuildConfigCostViewProperty property) { }
	// RVA: 0x270cf2c VA: 0x7594d24f2c
	private static Void _UpdateItemCard(RecruitBuildConfigCostCard costCard, UIItemViewModel viewModel, Int64 curCount) { }
	// RVA: 0x270cfec VA: 0x7594d24fec
	public Void .ctor() { }
}
```