# SandboxV2BattleFinishServiceConfig

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BattleFinishServiceConfig : FinishBattleServiceConfig`2
{
	private const Int32 FINISH_BATTLE_SERVICE_MAX_RETRY_COUNT; // 0x0
	private String m_topicId; // 0x18

	public override Int32 overrideMaxRetryCount { get; }

	// RVA: 0x2606bb0 VA: 0x7594c1ebb0
	public override Int32 get_overrideMaxRetryCount() { }
	// RVA: 0x2606bb8 VA: 0x7594c1ebb8
	public Void .ctor(String serviceCode, String topicId) { }
	// RVA: 0x2606c24 VA: 0x7594c1ec24
	public override Void OnParseRequest(SandboxV2BattleFinishRequest request) { }
}
```