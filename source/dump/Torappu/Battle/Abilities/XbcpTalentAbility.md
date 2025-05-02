# XbcpTalentAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 m_checkpointIndex`

- `Int32 m_checkpointCount`

- `Int32 m_finishRoundCount`


## Methods

- `Void <>xLuaBaseProxy_DoSetData(Entity, Options)`

- `Boolean <>xLuaBaseProxy_DealTargetTouched(Entity, TargetMeta)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class XbcpTalentAbility : AuraAbility
{
	private const String CHECKPOINT_INDEX; // 0x0
	private const String CHECKPOINT_COUNT; // 0x0
	private const String ROUND_COUNT; // 0x0
	private Int32 m_checkpointIndex; // 0x178
	private Int32 m_checkpointCount; // 0x17c
	private Int32 m_finishRoundCount; // 0x180
	private static DelegateBridge __Hotfix0_DoSetData; // 0x0
	private static DelegateBridge __Hotfix0_DealTargetTouched; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1eb7c24 VA: 0x75944cfc24
	protected override Void DoSetData(Entity owner, Options options) { }
	// RVA: 0x1eb7e3c VA: 0x75944cfe3c
	protected override Boolean DealTargetTouched(Entity target, TargetMeta meta) { }
	// RVA: 0x1eb8008 VA: 0x75944d0008
	public Void .ctor() { }
	// RVA: 0x1eb8078 VA: 0x75944d0078
	private Void <>xLuaBaseProxy_DoSetData(Entity P0, Options P1) { }
	// RVA: 0x1eb80a0 VA: 0x75944d00a0
	private Boolean <>xLuaBaseProxy_DealTargetTouched(Entity P0, TargetMeta P1) { }
}
```