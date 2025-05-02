# Act6FunBattleStartConfig

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `String m_stageId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_stageId; // 0x10
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x31af758 VA: 0x75957c7758
	protected override String get_serviceCode() { }
	// RVA: 0x31af7d4 VA: 0x75957c77d4
	public Void .ctor(String stageId) { }
	// RVA: 0x31af87c VA: 0x75957c787c
	protected override Act6FunBattleStartRequest ParseRequest() { }
}
```