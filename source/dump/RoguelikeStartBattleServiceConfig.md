# RoguelikeStartBattleServiceConfig

**Namespace:** ` `


## Fields

- `RoguelikeNodePosition m_toPos`

- `String m_stageId`

- `SquadModel m_squad`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RoguelikeStartBattleServiceConfig : StartBattleServiceConfig`2
{
	private RoguelikeNodePosition m_toPos; // 0x10
	private String m_stageId; // 0x18
	private SquadModel m_squad; // 0x20
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x2af72a8 VA: 0x759510f2a8
	protected override String get_serviceCode() { }
	// RVA: 0x2af5ea8 VA: 0x759510dea8
	public Void .ctor(RoguelikeNodePosition toPos, String stageId, SquadModel squad) { }
	// RVA: 0x2af7324 VA: 0x759510f324
	protected override RoguelikeStartBattleRequest ParseRequest() { }
}
```