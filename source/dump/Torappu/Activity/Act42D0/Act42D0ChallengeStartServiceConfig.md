# Act42D0ChallengeStartServiceConfig

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String m_actId`

- `String m_stageId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ChallengeStartServiceConfig : CrisisStartBattleServiceConfig`2
{
	private String m_actId; // 0x20
	private String m_stageId; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x32036cc VA: 0x759581b6cc
	public Void .ctor(String actId, String stageId) { }
	// RVA: 0x3203798 VA: 0x759581b798
	protected override String get_serviceCode() { }
	// RVA: 0x3203814 VA: 0x759581b814
	protected override Act42D0ChallengeBattleStartRequest ParseRequest() { }
}
```