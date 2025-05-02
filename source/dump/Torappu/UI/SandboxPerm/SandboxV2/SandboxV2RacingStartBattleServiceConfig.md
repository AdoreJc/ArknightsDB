# SandboxV2RacingStartBattleServiceConfig

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `String m_nodeId`

- `String m_racerInstId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacingStartBattleServiceConfig : StartBattleServiceConfig`2
{
	private String m_topicId; // 0x10
	private String m_nodeId; // 0x18
	private String m_racerInstId; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10

	protected override String serviceCode { get; }

	// RVA: 0x2606704 VA: 0x7594c1e704
	public Void .ctor(String topicId, String nodeId, String racerInstId) { }
	// RVA: 0x26067e8 VA: 0x7594c1e7e8
	protected override String get_serviceCode() { }
	// RVA: 0x2606864 VA: 0x7594c1e864
	protected override SandboxV2RacingBattleStartRequest ParseRequest() { }
}
```