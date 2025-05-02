# EnemyDuelStartMultiBattleServiceConfig

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `String m_activityId`

- `String m_sceneId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelStartMultiBattleServiceConfig : StartBattleServiceConfig`2
{
	private String m_activityId; // 0x10
	private String m_sceneId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x2943758 VA: 0x7594f5b758
	public Void .ctor(String activityId, String sceneId) { }
	// RVA: 0x2943824 VA: 0x7594f5b824
	protected override String get_serviceCode() { }
	// RVA: 0x29438a0 VA: 0x7594f5b8a0
	protected override EnemyDuelMultiBattleStartRequest ParseRequest() { }
}
```