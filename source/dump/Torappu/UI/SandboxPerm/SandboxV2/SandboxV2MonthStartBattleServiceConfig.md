# SandboxV2MonthStartBattleServiceConfig

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `Int32 m_squadIdx`

- `String m_monthRushId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2MonthStartBattleServiceConfig : StartBattleServiceConfig`2
{
	private String m_topicId; // 0x10
	private Int32 m_squadIdx; // 0x18
	private String m_monthRushId; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x8
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x260696c VA: 0x7594c1e96c
	public Void .ctor(String topicId, Int32 squadIdx, String monthRushId) { }
	// RVA: 0x2606a44 VA: 0x7594c1ea44
	protected override SandboxV2MonthBattleStartRequest ParseRequest() { }
	// RVA: 0x2606b0c VA: 0x7594c1eb0c
	protected override String get_serviceCode() { }
}
```