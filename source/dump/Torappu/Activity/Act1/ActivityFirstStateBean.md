# ActivityFirstStateBean

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `ActivityShopData cacheData`

- `ActivityFirstMapProperty mapProperty`


## Methods

- `Void InitMissionData()`

- `Void InitState(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstStateBean : ActivityStageSingleComponent, IStateBean, IHotfixable, IDataBindWrapper
{
	public List`1 missionList; // 0x20
	public List`1 cacheShopList; // 0x28
	public ActivityShopData cacheData; // 0x30
	public ActivityFirstMapProperty mapProperty; // 0x38
	private static DelegateBridge __Hotfix0_InitMissionData; // 0x0
	private static DelegateBridge __Hotfix0_InitState; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x348f028 VA: 0x7595aa7028
	public Void InitMissionData() { }
	// RVA: 0x348d380 VA: 0x7595aa5380
	public Void InitState(String activityId) { }
	// RVA: 0x3492788 VA: 0x7595aaa788
	public Void .ctor() { }
}
```