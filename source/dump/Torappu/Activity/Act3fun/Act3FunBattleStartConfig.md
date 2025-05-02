# Act3FunBattleStartConfig

**Namespace:** `Torappu.Activity.Act3fun`


## Fields

- `String m_stageId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3fun
public class Act3FunBattleStartConfig : StartBattleServiceConfig`2
{
	private String m_stageId; // 0x10
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x322254c VA: 0x759583a54c
	protected override String get_serviceCode() { }
	// RVA: 0x32225c8 VA: 0x759583a5c8
	public Void .ctor(String stageId) { }
	// RVA: 0x3222670 VA: 0x759583a670
	protected override Act3FunBattleStartRequst ParseRequest() { }
}
```