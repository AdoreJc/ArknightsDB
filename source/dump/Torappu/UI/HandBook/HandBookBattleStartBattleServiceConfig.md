# HandBookBattleStartBattleServiceConfig

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `String m_charId`

- `String m_stageId`

- `SquadModel m_squad`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookBattleStartBattleServiceConfig : StartBattleServiceConfig`2
{
	private String m_charId; // 0x10
	private String m_stageId; // 0x18
	private SquadModel m_squad; // 0x20
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x2e9b22c VA: 0x75954b322c
	protected override String get_serviceCode() { }
	// RVA: 0x2e9b2a8 VA: 0x75954b32a8
	public Void .ctor(String charId, String stageId, SquadModel squad) { }
	// RVA: 0x2e9b38c VA: 0x75954b338c
	protected override HandBookAddonStageBattleStartRequest ParseRequest() { }
}
```