# Act1BossRushMileStoneViewModel

**Namespace:** `Torappu.Activity.Act1BossRush`


## Fields

- `Int32 focusIndex`

- `String mainItemDesc`

- `String rewardSkinId`

- `MilestoneStruct milestoneStruct`

- `Boolean hasItemCanReceive`

- `Int32 m_point`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1BossRush
public class Act1BossRushMileStoneViewModel : IHotfixable
{
	public List`1 dataSet; // 0x10
	public Dictionary`2 itemStateMap; // 0x18
	public Int32 focusIndex; // 0x20
	public String mainItemDesc; // 0x28
	public String rewardSkinId; // 0x30
	public MilestoneStruct milestoneStruct; // 0x38
	public Boolean hasItemCanReceive; // 0x48
	private Int32 m_point; // 0x4c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3193de4 VA: 0x75957abde4
	public Void LoadData(String actId) { }
	// RVA: 0x3194420 VA: 0x75957ac420
	public Void .ctor() { }
}
```