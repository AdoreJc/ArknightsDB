# StartServiceConfig

**Namespace:** ` `


## Fields

- `Param m_param`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class StartServiceConfig : StartBattleServiceConfig`2
{
	private Param m_param; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x23788d8 VA: 0x75949908d8
	public Void .ctor(Param param) { }
	// RVA: 0x2379ad4 VA: 0x7594991ad4
	protected override String get_serviceCode() { }
	// RVA: 0x2379b50 VA: 0x7594991b50
	protected override RuneStartBattleRequest ParseRequest() { }
}
```