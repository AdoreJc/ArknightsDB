# ActivityTextStageTime

**Namespace:** `Torappu.Activity`


## Fields

- `Text _detailText`

- `String _rewardString`

- `String _stageString`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityTextStageTime : AbstractStageTime
{
	private Text _detailText; // 0x18
	private String _rewardString; // 0x20
	private String _stageString; // 0x28
	private static DelegateBridge __Hotfix0_SetRewardTimeActive; // 0x0
	private static DelegateBridge __Hotfix0_SetStageTimeActive; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30c44e8 VA: 0x75956dc4e8
	public override Void SetRewardTimeActive(Boolean isActive) { }
	// RVA: 0x30c457c VA: 0x75956dc57c
	public override Void SetStageTimeActive(Boolean isActive) { }
	// RVA: 0x30c4610 VA: 0x75956dc610
	public Void .ctor() { }
}
```