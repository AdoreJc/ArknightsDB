# EnemyDuelStartSingleBattleServiceConfig

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String m_activityId`

- `String m_modeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelStartSingleBattleServiceConfig : StartBattleServiceConfig`2
{
	private String m_activityId; // 0x10
	private String m_modeId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x2943988 VA: 0x7594f5b988
	public Void .ctor(String activityId, String modeId) { }
	// RVA: 0x2943a54 VA: 0x7594f5ba54
	protected override String get_serviceCode() { }
	// RVA: 0x2943ad0 VA: 0x7594f5bad0
	protected override EnemyDuelSingleBattleStartRequest ParseRequest() { }
}
```