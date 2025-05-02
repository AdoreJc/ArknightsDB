# Act1LockInterlockBattleStartConfig

**Namespace:** `Torappu.Activity.Act1Lock`


## Fields

- `String m_activityId`

- `String m_stageId`

- `Boolean m_useSpecial`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock
public class Act1LockInterlockBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_activityId; // 0x10
	private String m_stageId; // 0x18
	private Boolean m_useSpecial; // 0x20
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x3394578 VA: 0x75959ac578
	protected override String get_serviceCode() { }
	// RVA: 0x33945f4 VA: 0x75959ac5f4
	public Void .ctor(String activityId, String stageId, Boolean useSpecial) { }
	// RVA: 0x33946e0 VA: 0x75959ac6e0
	protected override Act1LockInterlockBattleStartRequest ParseRequest() { }
}
```