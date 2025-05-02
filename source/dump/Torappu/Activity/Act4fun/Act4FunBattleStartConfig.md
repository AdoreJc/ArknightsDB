# Act4FunBattleStartConfig

**Namespace:** `Torappu.Activity.Act4fun`


## Fields

- `String m_stageId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4fun
public class Act4FunBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_stageId; // 0x10
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x31c317c VA: 0x75957db17c
	protected override String get_serviceCode() { }
	// RVA: 0x31c31f8 VA: 0x75957db1f8
	public Void .ctor(String stageId) { }
	// RVA: 0x31c32a0 VA: 0x75957db2a0
	protected override Act4FunBattleStartRequst ParseRequest() { }
}
```