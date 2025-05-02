# Act1LockFinalBattleStartConfig

**Namespace:** `Torappu.Activity.Act1Lock`


## Fields

- `String m_activityId`

- `String m_stageId`

- `Boolean m_useSpecial`

- `Boolean m_usePracticeTicket`

- `Boolean m_isReplay`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock
public class Act1LockFinalBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_activityId; // 0x10
	private String m_stageId; // 0x18
	private Boolean m_useSpecial; // 0x20
	private Boolean m_usePracticeTicket; // 0x21
	private Boolean m_isReplay; // 0x22
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x33948ac VA: 0x75959ac8ac
	protected override String get_serviceCode() { }
	// RVA: 0x3394928 VA: 0x75959ac928
	public Void .ctor(String activityId, String stageId, Boolean useSpecial, Boolean usePt, Boolean isReplay) { }
	// RVA: 0x3394a40 VA: 0x75959aca40
	protected override Act1LockFinalBattleStartRequest ParseRequest() { }
}
```