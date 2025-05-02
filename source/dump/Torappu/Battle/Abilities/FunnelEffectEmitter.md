# FunnelEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _useIdleBackEffect`

- `Boolean _useOverloadEffect`

- `Boolean _setActiveFalseWhenPause`

- `Boolean m_cachedIsBack`

- `Boolean m_isIdle`

- `Boolean m_isOwnerOverloading`

- `Character m_funnelOwner`


## Properties

- `Boolean useIdleBackEffect`

- `Boolean useOverloadEffect`


## Methods

- `Boolean get_useIdleBackEffect()`

- `Boolean get_useOverloadEffect()`

- `Void Update()`

- `Void _UpdateFace(Boolean)`

- `Void _UpdateIdleEffect()`

- `Effect _PlayEffect(String)`

- `Boolean _CheckOwnerOverloadState()`

- `Void <>xLuaBaseProxy_Init(AbilityStandard)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class FunnelEffectEmitter : AbstractEffectEmitter
{
	private Boolean _useIdleBackEffect; // 0x20
	private String[] _idleEffect; // 0x28
	private String[] _idleBackEffect; // 0x30
	private String[] _disappearEffect; // 0x38
	private String[] _appearEffect; // 0x40
	private Boolean _useOverloadEffect; // 0x48
	private Boolean _setActiveFalseWhenPause; // 0x49
	private String[] _overloadIdleEffect; // 0x50
	private Boolean m_cachedIsBack; // 0x58
	private Boolean m_isIdle; // 0x59
	private Boolean m_isOwnerOverloading; // 0x5a
	private Character m_funnelOwner; // 0x60
	private List`1 m_idleEffect; // 0x68
	private List`1 m_idleBackEffect; // 0x70
	private static DelegateBridge __Hotfix0_get_useIdleBackEffect; // 0x0
	private static DelegateBridge __Hotfix0_get_useOverloadEffect; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0__UpdateFace; // 0x28
	private static DelegateBridge __Hotfix0_OnEvent; // 0x30
	private static DelegateBridge __Hotfix0__UpdateIdleEffect; // 0x38
	private static DelegateBridge __Hotfix0__PlayEffect; // 0x40
	private static DelegateBridge __Hotfix0__CheckOwnerOverloadState; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Boolean useIdleBackEffect { get; }
	private Boolean useOverloadEffect { get; }

	// RVA: 0x1ec374c VA: 0x75944db74c
	private Boolean get_useIdleBackEffect() { }
	// RVA: 0x1ec37b4 VA: 0x75944db7b4
	private Boolean get_useOverloadEffect() { }
	// RVA: 0x1ec381c VA: 0x75944db81c
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec395c VA: 0x75944db95c
	public override Void Init(AbilityStandard ability) { }
	// RVA: 0x1ec3a58 VA: 0x75944dba58
	private Void Update() { }
	// RVA: 0x1ec3cac VA: 0x75944dbcac
	private Void _UpdateFace(Boolean force) { }
	// RVA: 0x1ec43f8 VA: 0x75944dc3f8
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec3ffc VA: 0x75944dbffc
	private Void _UpdateIdleEffect() { }
	// RVA: 0x1ec3edc VA: 0x75944dbedc
	private Effect _PlayEffect(String effectKey) { }
	// RVA: 0x1ec3dc0 VA: 0x75944dbdc0
	private Boolean _CheckOwnerOverloadState() { }
	// RVA: 0x1ec4dc4 VA: 0x75944dcdc4
	public Void .ctor() { }
	// RVA: 0x1ec4eb8 VA: 0x75944dceb8
	private Void <>xLuaBaseProxy_Init(AbilityStandard P0) { }
	// RVA: 0x1ec4ec0 VA: 0x75944dcec0
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```