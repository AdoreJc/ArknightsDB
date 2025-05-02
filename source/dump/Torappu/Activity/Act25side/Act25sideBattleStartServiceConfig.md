# Act25sideBattleStartServiceConfig

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Int32 continuousBattleTimes`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideBattleStartServiceConfig : SquadCustomStartBattleServiceConfig`2
{
	public Int32 continuousBattleTimes; // 0x18
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge __Hotfix0_OnParseRequest; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x326f12c VA: 0x759588712c
	protected override String get_serviceCode() { }
	// RVA: 0x326f1a8 VA: 0x75958871a8
	protected override Void OnParseRequest(Act25sideBattleStartRequest request) { }
	// RVA: 0x326f2c0 VA: 0x75958872c0
	public Void .ctor(Param param) { }
}
```