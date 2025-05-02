# RewardListAdpater

**Namespace:** ` `


## Methods

- `Void SetData(List`1)`

- `Void set_onTrialCollect(Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class RewardListAdpater : SimpleLayoutAdapter
{
	private List`1 m_rewardList; // 0x20
	private Action`2 <onTrialCollect>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_get_onTrialCollect; // 0x10
	private static DelegateBridge __Hotfix0_set_onTrialCollect; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Int32 count { get; }
	private Action`2 onTrialCollect { get; set; }

	// RVA: 0x274a4bc VA: 0x7594d624bc
	public Void SetData(List`1 rewardList) { }
	// RVA: 0x274a8e0 VA: 0x7594d628e0
	public override Int32 get_count() { }
	// RVA: 0x274a960 VA: 0x7594d62960
	private Action`2 get_onTrialCollect() { }
	// RVA: 0x2749b84 VA: 0x7594d61b84
	public Void set_onTrialCollect(Action`2 value) { }
	// RVA: 0x274a9c8 VA: 0x7594d629c8
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2749b14 VA: 0x7594d61b14
	public Void .ctor() { }
}
```