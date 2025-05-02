# DIYRecycleHorizontalAdapter

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DIYRecycleElementView m_prefab`

- `DIYRecycleElementView m_emptyPrefab`


## Methods

- `Void set_dataSource(List`1)`

- `Void set_funcDataSource(List`1)`

- `Void Rebuild()`

- `Void TryUpdateItemViews()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYRecycleHorizontalAdapter : UIRecycleLayoutAdapter
{
	public Func`2 OnButtonSelected; // 0x18
	public Func`2 OnButtonInfo; // 0x20
	private DIYRecycleElementView m_prefab; // 0x28
	private DIYRecycleElementView m_emptyPrefab; // 0x30
	private List`1 m_viewDatas; // 0x38
	private List`1 m_funcViewDatas; // 0x40
	private List`1 m_views; // 0x48
	private static DelegateBridge __Hotfix0_get_dataSource; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSource; // 0x8
	private static DelegateBridge __Hotfix0_get_funcDataSource; // 0x10
	private static DelegateBridge __Hotfix0_set_funcDataSource; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge __Hotfix0_Rebuild; // 0x28
	private static DelegateBridge __Hotfix0_TryUpdateItemViews; // 0x30
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x38

	public List`1 dataSource { get; set; }
	public List`1 funcDataSource { get; set; }

	// RVA: 0x382bb2c VA: 0x7595e43b2c
	public List`1 get_dataSource() { }
	// RVA: 0x382bb94 VA: 0x7595e43b94
	public Void set_dataSource(List`1 value) { }
	// RVA: 0x382bc18 VA: 0x7595e43c18
	public List`1 get_funcDataSource() { }
	// RVA: 0x382bc80 VA: 0x7595e43c80
	public Void set_funcDataSource(List`1 value) { }
	// RVA: 0x382bd04 VA: 0x7595e43d04
	public Void .ctor(List`1 data, List`1 funcData, DIYRecycleElementView prefab, DIYRecycleElementView emptyPrefab) { }
	// RVA: 0x382beac VA: 0x7595e43eac
	public Void Rebuild() { }
	// RVA: 0x382bf94 VA: 0x7595e43f94
	public Void TryUpdateItemViews() { }
	// RVA: 0x382c14c VA: 0x7595e4414c
	public override IList`1 GenerateViewsForRebuild() { }
}
```