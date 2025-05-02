# TemplateMissionCommonListView

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `UIRecycleVerticalLayoutGroup _recycleList`

- `TemplateMissionCommonEntryFadeTween _entryFadeTween`

- `Boolean m_isInited`

- `TemplateMissionCommonListAdapter m_adapter`

- `TemplateMissionCommonItemClaimAllView m_claimAllViewPrefab`

- `TemplateMissionCommonItemNormalView m_itemNormalViewPrefab`

- `AbstractTemplateMissionRewardItemView m_rewardItemViewPrefab`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_Init(AbstractTemplateMissionViewController, TemplateMissionCustomResHolder)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionCommonListView : TemplateMissionListView
{
	private UIRecycleVerticalLayoutGroup _recycleList; // 0x40
	private TemplateMissionCommonEntryFadeTween _entryFadeTween; // 0x48
	private Boolean m_isInited; // 0x50
	private TemplateMissionCommonListAdapter m_adapter; // 0x58
	private TemplateMissionCommonItemClaimAllView m_claimAllViewPrefab; // 0x60
	private TemplateMissionCommonItemNormalView m_itemNormalViewPrefab; // 0x68
	private AbstractTemplateMissionRewardItemView m_rewardItemViewPrefab; // 0x70
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_BindPrefabToListView; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x236a498 VA: 0x7594982498
	public override Void Init(AbstractTemplateMissionViewController ctrl_, TemplateMissionCustomResHolder customResHolder_) { }
	// RVA: 0x236a608 VA: 0x7594982608
	public override Void BindPrefabToListView(AbstractTemplateMissionItemClaimAllView claimAllViewPrefab, AbstractTemplateMissionItemNormalView itemNormalViewPrefab, AbstractTemplateMissionRewardItemView rewardItemViewPrefab) { }
	// RVA: 0x236a864 VA: 0x7594982864
	protected override Void RenderView() { }
	// RVA: 0x236a538 VA: 0x7594982538
	private Void _InitIfNot() { }
	// RVA: 0x236aeb4 VA: 0x7594982eb4
	public Void .ctor() { }
	// RVA: 0x236af8c VA: 0x7594982f8c
	private Void <>xLuaBaseProxy_Init(AbstractTemplateMissionViewController P0, TemplateMissionCustomResHolder P1) { }
}
```