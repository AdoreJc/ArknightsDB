# Act42D0NormalStartServiceConfig

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String m_actId`

- `String m_stageId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0NormalStartServiceConfig : CrisisStartBattleServiceConfig`2
{
	private String m_actId; // 0x20
	private String m_stageId; // 0x28
	private List`1 m_buffList; // 0x30
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x3203558 VA: 0x759581b558
	protected override String get_serviceCode() { }
	// RVA: 0x3202690 VA: 0x759581a690
	public Void .ctor(String actId, String stageId, List`1 buffList) { }
	// RVA: 0x32035d4 VA: 0x759581b5d4
	protected override Act42D0NormalBattleStartRequest ParseRequest() { }
}
```