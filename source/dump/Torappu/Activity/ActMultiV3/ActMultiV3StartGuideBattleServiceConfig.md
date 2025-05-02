# ActMultiV3StartGuideBattleServiceConfig

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String m_actId`

- `String m_stageId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3StartGuideBattleServiceConfig : StartBattleServiceConfig`2
{
	private String m_actId; // 0x10
	private String m_stageId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x30dc3bc VA: 0x75956f43bc
	public Void .ctor(String actId, String stageId) { }
	// RVA: 0x30dc488 VA: 0x75956f4488
	protected override String get_serviceCode() { }
	// RVA: 0x30dc504 VA: 0x75956f4504
	protected override ActMultiV3GuideBattleStartRequest ParseRequest() { }
}
```