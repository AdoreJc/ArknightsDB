# Act5FunBattleStartConfig

**Namespace:** `Torappu.Activity.Act5fun`


## Fields

- `String m_stageId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5fun
public class Act5FunBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_stageId; // 0x10
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x31b89ac VA: 0x75957d09ac
	protected override String get_serviceCode() { }
	// RVA: 0x31b8a28 VA: 0x75957d0a28
	public Void .ctor(String stageId) { }
	// RVA: 0x31b8ad0 VA: 0x75957d0ad0
	protected override Act5FunBattleStartRequst ParseRequest() { }
}
```