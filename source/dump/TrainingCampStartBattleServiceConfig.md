# TrainingCampStartBattleServiceConfig

**Namespace:** ` `


## Fields

- `String m_stageId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TrainingCampStartBattleServiceConfig : StartBattleServiceConfig`2
{
	private String m_stageId; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x234bb0c VA: 0x7594963b0c
	public Void .ctor(String stageId) { }
	// RVA: 0x234bf34 VA: 0x7594963f34
	protected override String get_serviceCode() { }
	// RVA: 0x234bfb0 VA: 0x7594963fb0
	protected override TrainingCampStartBattleRequest ParseRequest() { }
}
```