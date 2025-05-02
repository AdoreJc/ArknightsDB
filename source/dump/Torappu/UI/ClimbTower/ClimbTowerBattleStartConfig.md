# ClimbTowerBattleStartConfig

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `String m_stageId`

- `SquadModel m_squad`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_stageId; // 0x10
	private SquadModel m_squad; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x8
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x2c727d0 VA: 0x759528a7d0
	public Void .ctor(String stageId, SquadModel squad) { }
	// RVA: 0x2c7289c VA: 0x759528a89c
	protected override ClimbTowerBattleStartRequest ParseRequest() { }
	// RVA: 0x2c72954 VA: 0x759528a954
	protected override String get_serviceCode() { }
}
```