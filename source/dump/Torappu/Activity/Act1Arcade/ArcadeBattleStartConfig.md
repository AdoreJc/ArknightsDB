# ArcadeBattleStartConfig

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `String m_stageId`

- `String m_activityId`

- `SquadModel m_squadModel`

- `SquadFriendData m_assistFriend`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class ArcadeBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_stageId; // 0x10
	private String m_activityId; // 0x18
	private SquadModel m_squadModel; // 0x20
	private SquadFriendData m_assistFriend; // 0x28
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x33eedc4 VA: 0x7595a06dc4
	protected override String get_serviceCode() { }
	// RVA: 0x33eee40 VA: 0x7595a06e40
	public Void .ctor(String activityId, String stageId, SquadModel squadModel, SquadFriendData assistFriend) { }
	// RVA: 0x33eef48 VA: 0x7595a06f48
	protected override ArcadeStartBattleRequest ParseRequest() { }
}
```