# VecBreakBattleStartConfig

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `String m_stageId`

- `SquadModel m_squadModel`

- `SquadFriendData m_assistFriend`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_stageId; // 0x10
	private SquadModel m_squadModel; // 0x18
	private SquadFriendData m_assistFriend; // 0x20
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x22e1bf4 VA: 0x75948f9bf4
	protected override String get_serviceCode() { }
	// RVA: 0x22dcb98 VA: 0x75948f4b98
	public Void .ctor(String stageId, SquadModel squadModel, SquadFriendData assistFriend) { }
	// RVA: 0x22e1c70 VA: 0x75948f9c70
	protected override VecBreakStartBattleRequest ParseRequest() { }
}
```