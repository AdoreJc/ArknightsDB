# SandboxV2RacingBattleFinishServiceConfig

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacingBattleFinishServiceConfig : FinishBattleServiceConfig`2
{
	private const Int32 FINISH_BATTLE_SERVICE_MAX_RETRY_COUNT; // 0x0
	private String m_topicId; // 0x18

	public override Int32 overrideMaxRetryCount { get; }

	// RVA: 0x2606d10 VA: 0x7594c1ed10
	public override Int32 get_overrideMaxRetryCount() { }
	// RVA: 0x2606d18 VA: 0x7594c1ed18
	public Void .ctor(String serviceCode, String topicId) { }
	// RVA: 0x2606d84 VA: 0x7594c1ed84
	public override Void OnParseRequest(SandboxV2RacingBattleFinishRequest request) { }
}
```