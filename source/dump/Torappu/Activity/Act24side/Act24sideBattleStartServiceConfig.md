# Act24sideBattleStartServiceConfig

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `String m_activityId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleStartServiceConfig : SquadCustomStartBattleServiceConfig`2
{
	private String m_activityId; // 0x18
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge __Hotfix0_OnParseRequest; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x328f490 VA: 0x75958a7490
	protected override String get_serviceCode() { }
	// RVA: 0x328f50c VA: 0x75958a750c
	protected override Void OnParseRequest(Act24sideBattleStartRequest request) { }
	// RVA: 0x328f5bc VA: 0x75958a75bc
	public Void .ctor(Param param) { }
}
```