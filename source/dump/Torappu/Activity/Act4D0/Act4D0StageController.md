# Act4D0StageController

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `Act4D0InitMeta m_initMetaObj`


## Properties

- `Act4D0InitMeta initMetaObj`


## Methods

- `Act4D0InitMeta get_initMetaObj()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0StageController : ActivityStageController
{
	private Act4D0InitMeta m_initMetaObj; // 0x60
	private static DelegateBridge __Hotfix0_get_staticActivityId; // 0x0
	private static DelegateBridge __Hotfix0_get_initMetaObj; // 0x8
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x10
	private static DelegateBridge __Hotfix0_CreateInitMeta4StoryState; // 0x18
	private static DelegateBridge __Hotfix0_GetAct4D0PlayerInfo; // 0x20
	private static DelegateBridge __Hotfix0_GetAct4D0PlayerInfoFromPlayerData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public static String staticActivityId { get; }
	public Act4D0InitMeta initMetaObj { get; }

	// RVA: 0x31da348 VA: 0x75957f2348
	public static String get_staticActivityId() { }
	// RVA: 0x31da940 VA: 0x75957f2940
	public Act4D0InitMeta get_initMetaObj() { }
	// RVA: 0x31daa00 VA: 0x75957f2a00
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x31daad8 VA: 0x75957f2ad8
	public static String CreateInitMeta4StoryState() { }
	// RVA: 0x31da424 VA: 0x75957f2424
	public static PlayerAct4D0Activity GetAct4D0PlayerInfo(String actId) { }
	// RVA: 0x31dab74 VA: 0x75957f2b74
	public static PlayerAct4D0Activity GetAct4D0PlayerInfoFromPlayerData(String actId, PlayerDataModel playerModel) { }
	// RVA: 0x31dac34 VA: 0x75957f2c34
	public Void .ctor() { }
}
```