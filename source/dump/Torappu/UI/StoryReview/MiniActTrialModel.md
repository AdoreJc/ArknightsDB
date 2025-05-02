# MiniActTrialModel

**Namespace:** `Torappu.UI.StoryReview`


## Properties

- `MiniActTrialItemModel firstTrialItem`


## Methods

- `MiniActTrialItemModel get_firstTrialItem()`

- `Void LoadData(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class MiniActTrialModel : IHotfixable
{
	private List`1 m_trialItemList; // 0x10
	private static DelegateBridge __Hotfix0_get_trialItemList; // 0x0
	private static DelegateBridge __Hotfix0_get_firstTrialItem; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public List`1 trialItemList { get; }
	public MiniActTrialItemModel firstTrialItem { get; }

	// RVA: 0x2748cb8 VA: 0x7594d60cb8
	public List`1 get_trialItemList() { }
	// RVA: 0x274d1a0 VA: 0x7594d651a0
	public MiniActTrialItemModel get_firstTrialItem() { }
	// RVA: 0x274d22c VA: 0x7594d6522c
	public Void LoadData(List`1 storyIdList) { }
	// RVA: 0x274d480 VA: 0x7594d65480
	public Void .ctor() { }
}
```