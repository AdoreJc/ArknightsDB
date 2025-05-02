# SandboxV2StartBattleServiceConfig

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `String m_nodeId`

- `Int32 m_squadIdx`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2StartBattleServiceConfig : StartBattleServiceConfig`2
{
	private String m_topicId; // 0x10
	private String m_nodeId; // 0x18
	private Int32 m_squadIdx; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x2606394 VA: 0x7594c1e394
	public Void .ctor(String topicId, String nodeId, Int32 squadIdx) { }
	// RVA: 0x2606470 VA: 0x7594c1e470
	protected override String get_serviceCode() { }
	// RVA: 0x26064ec VA: 0x7594c1e4ec
	protected override SandboxV2BattleStartRequest ParseRequest() { }
}
```