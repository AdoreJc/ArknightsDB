# ActMultiV3StartBattleServiceConfig

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String m_actId`

- `String m_sceneId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StartBattleServiceConfig : StartBattleServiceConfig`2
{
	private String m_actId; // 0x10
	private String m_sceneId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x30dc780 VA: 0x75956f4780
	public Void .ctor(String actId, String sceneId) { }
	// RVA: 0x30dc84c VA: 0x75956f484c
	protected override String get_serviceCode() { }
	// RVA: 0x30dc8c8 VA: 0x75956f48c8
	protected override ActMultiV3BattleStartRequest ParseRequest() { }
}
```