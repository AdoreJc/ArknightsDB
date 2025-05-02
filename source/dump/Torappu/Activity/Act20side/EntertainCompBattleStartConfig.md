# EntertainCompBattleStartConfig

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String m_activityId`

- `String m_stageId`

- `Cart m_car`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class EntertainCompBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_activityId; // 0x10
	private String m_stageId; // 0x18
	private Cart m_car; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x8
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x32eb888 VA: 0x7595903888
	public Void .ctor(String actId, String stageId, Cart car) { }
	// RVA: 0x32eb96c VA: 0x759590396c
	protected override CarCompetitionStartRequest ParseRequest() { }
	// RVA: 0x32eba34 VA: 0x7595903a34
	protected override String get_serviceCode() { }
}
```