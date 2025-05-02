# Act1BossRushEntryMileStoneButtonViewModel

**Namespace:** `Torappu.Activity.Act1BossRush`


## Methods

- `MilestoneStruct GetMilestoneStruct()`

- `Boolean HasRewardCanClaim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushEntryMileStoneButtonViewModel : TemplateActivityViewModel, IHotfixable
{
	private Func`1 m_getMilestoneStructFunc; // 0x20
	private Func`1 m_hasMileStoneRewardFunc; // 0x28
	private static DelegateBridge __Hotfix0_GetMilestoneStruct; // 0x0
	private static DelegateBridge __Hotfix0_HasRewardCanClaim; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x318f58c VA: 0x75957a758c
	public MilestoneStruct GetMilestoneStruct() { }
	// RVA: 0x318f638 VA: 0x75957a7638
	public Boolean HasRewardCanClaim() { }
	// RVA: 0x318df20 VA: 0x75957a5f20
	public Void .ctor(Object param) { }
}
```