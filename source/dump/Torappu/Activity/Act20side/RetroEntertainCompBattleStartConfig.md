# RetroEntertainCompBattleStartConfig

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `String m_retroId`

- `String m_stageId`

- `Cart m_car`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class RetroEntertainCompBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_retroId; // 0x10
	private String m_stageId; // 0x18
	private Cart m_car; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x8
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x32ebab0 VA: 0x7595903ab0
	public Void .ctor(String retroId, String stageId, Cart car) { }
	// RVA: 0x32ebb94 VA: 0x7595903b94
	protected override RetroCarCompetitionStartRequest ParseRequest() { }
	// RVA: 0x32ebc5c VA: 0x7595903c5c
	protected override String get_serviceCode() { }
}
```