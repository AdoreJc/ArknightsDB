# BossRushBattleStartConfig

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `String m_actId`

- `String m_stageId`

- `String m_teamId`

- `SquadFriendData m_assistFriend`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_actId; // 0x10
	private String m_stageId; // 0x18
	private String m_teamId; // 0x20
	private List`1 m_ownSlots; // 0x28
	private SquadFriendData m_assistFriend; // 0x30
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x2e59b38 VA: 0x7595471b38
	protected override String get_serviceCode() { }
	// RVA: 0x2e59bb4 VA: 0x7595471bb4
	public Void .ctor(String activityId, String stageId, String teamId, List`1 ownSlots, SquadFriendData assistFriend) { }
	// RVA: 0x2e59cd4 VA: 0x7595471cd4
	protected override BossRushStartBattleRequest ParseRequest() { }
}
```