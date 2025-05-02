# LineEffectEmitterDynamic

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _startEffect`

- `String _midEffect`

- `String _endEffect`

- `MountPointType _startMountPointType`

- `MountPointType _endMountPointType`

- `Boolean _finishIfEitherOfOwnersNotExist`

- `Boolean _finishIfEitherOfOwnersNotAliveOrReborn`

- `String _effectGeneratedOnTargetIfFinish`

- `String _effectGeneratedOnSourceIfFinish`

- `Boolean _pauseWhenDisappear`

- `Boolean _tweenEndPosition`

- `Single _tweenDuration`

- `Boolean _forceLineUseWorldSpace`

- `Boolean _useSelfEffectOnly`

- `Boolean _fetchStartEndViaBuff`

- `String _buffKey`

- `Boolean _finishIfBuffNotExists`

- `String _buffKeyForFinish`

- `Boolean _checkBuffSourceForFinish`

- `Boolean m_fetchedStartEndViaBuff`

- `Vector3 m_startPosition`

- `Vector3 m_endPosition`

- `Single m_lerpTime`


## Properties

- `Boolean finishIfBuffNotExists`

- `Boolean hasStartEffect`

- `Boolean hasMidEffect`

- `Boolean hasEndEffect`

- `Boolean tweenEndPosition`

- `Effect startEffect`

- `Effect endEffect`

- `Entity startPointOwner`

- `Entity endPointOwner`


## Methods

- `Boolean get_finishIfBuffNotExists()`

- `Boolean get_hasStartEffect()`

- `Boolean get_hasMidEffect()`

- `Boolean get_hasEndEffect()`

- `Boolean get_tweenEndPosition()`

- `Effect get_startEffect()`

- `Effect get_endEffect()`

- `Entity get_startPointOwner()`

- `Void set_startPointOwner(Entity)`

- `Entity get_endPointOwner()`

- `Void set_endPointOwner(Entity)`

- `Void Update()`

- `Boolean _TryDestroyIfOwnerNotExist()`

- `Boolean _TryDestroyIfOwnerNotAliveOrReborn()`

- `Boolean _TryDestroyIfBuffNotExist()`

- `Void _PauseIfDisappear()`

- `Void _FetchStartEndViaBuff()`

- `Void _TryUpdateEffects()`

- `Void _RefreshMidPositions()`

- `Void GatherEffects(List`1)`

- `Void ChangeEffectsExt(String)`

- `Void _UpdateMountPoint()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class LineEffectEmitterDynamic : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _startEffect; // 0x20
	private String _midEffect; // 0x28
	private String _endEffect; // 0x30
	private MountPointType _startMountPointType; // 0x38
	private MountPointType _endMountPointType; // 0x3c
	private Boolean _finishIfEitherOfOwnersNotExist; // 0x40
	private Boolean _finishIfEitherOfOwnersNotAliveOrReborn; // 0x41
	private String _effectGeneratedOnTargetIfFinish; // 0x48
	private String _effectGeneratedOnSourceIfFinish; // 0x50
	private Boolean _pauseWhenDisappear; // 0x58
	private Boolean _tweenEndPosition; // 0x59
	private Single _tweenDuration; // 0x5c
	private Boolean _forceLineUseWorldSpace; // 0x60
	private Boolean _useSelfEffectOnly; // 0x61
	private Boolean _fetchStartEndViaBuff; // 0x62
	private String _buffKey; // 0x68
	private Boolean _finishIfBuffNotExists; // 0x70
	private String _buffKeyForFinish; // 0x78
	private Boolean _checkBuffSourceForFinish; // 0x80
	private ObjectPtr`1 m_startPointOwner; // 0x88
	private ObjectPtr`1 m_endPointOwner; // 0x98
	private List`1 m_lineRenderers; // 0xa8
	private ObjectPtr`1 m_startEffect; // 0xb0
	private ObjectPtr`1 m_endEffect; // 0xc0
	private List`1 m_midEffects; // 0xd0
	private Boolean m_fetchedStartEndViaBuff; // 0xd8
	private Vector3 m_startPosition; // 0xdc
	private Vector3 m_endPosition; // 0xe8
	private List`1 m_midPositions; // 0xf8
	private Single m_lerpTime; // 0x100
	private static DelegateBridge __Hotfix0_get_finishIfBuffNotExists; // 0x0
	private static DelegateBridge __Hotfix0_get_hasStartEffect; // 0x8
	private static DelegateBridge __Hotfix0_get_hasMidEffect; // 0x10
	private static DelegateBridge __Hotfix0_get_hasEndEffect; // 0x18
	private static DelegateBridge __Hotfix0_get_tweenEndPosition; // 0x20
	private static DelegateBridge __Hotfix0_get_startEffect; // 0x28
	private static DelegateBridge __Hotfix0_get_endEffect; // 0x30
	private static DelegateBridge __Hotfix0_get_startPointOwner; // 0x38
	private static DelegateBridge __Hotfix0_set_startPointOwner; // 0x40
	private static DelegateBridge __Hotfix0_get_endPointOwner; // 0x48
	private static DelegateBridge __Hotfix0_set_endPointOwner; // 0x50
	private static DelegateBridge __Hotfix0_OnPlay; // 0x58
	private static DelegateBridge __Hotfix0_Update; // 0x60
	private static DelegateBridge __Hotfix0__TryDestroyIfOwnerNotExist; // 0x68
	private static DelegateBridge __Hotfix0__TryDestroyIfOwnerNotAliveOrReborn; // 0x70
	private static DelegateBridge __Hotfix0__TryDestroyIfBuffNotExist; // 0x78
	private static DelegateBridge __Hotfix0__PauseIfDisappear; // 0x80
	private static DelegateBridge __Hotfix0__FetchStartEndViaBuff; // 0x88
	private static DelegateBridge __Hotfix0__TryUpdateEffects; // 0x90
	private static DelegateBridge __Hotfix0__RefreshMidPositions; // 0x98
	private static DelegateBridge __Hotfix0_OnFinish; // 0xa0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0xa8
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateMountPoint; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	private Boolean finishIfBuffNotExists { get; }
	private Boolean hasStartEffect { get; }
	private Boolean hasMidEffect { get; }
	private Boolean hasEndEffect { get; }
	private Boolean tweenEndPosition { get; }
	private Effect startEffect { get; }
	private Effect endEffect { get; }
	public Entity startPointOwner { get; set; }
	public Entity endPointOwner { get; set; }

	// RVA: 0x1fff0e0 VA: 0x75946170e0
	private Boolean get_finishIfBuffNotExists() { }
	// RVA: 0x1fff148 VA: 0x7594617148
	private Boolean get_hasStartEffect() { }
	// RVA: 0x1fff1c0 VA: 0x75946171c0
	private Boolean get_hasMidEffect() { }
	// RVA: 0x1fff238 VA: 0x7594617238
	private Boolean get_hasEndEffect() { }
	// RVA: 0x1fff2b0 VA: 0x75946172b0
	private Boolean get_tweenEndPosition() { }
	// RVA: 0x1fff318 VA: 0x7594617318
	private Effect get_startEffect() { }
	// RVA: 0x1fff430 VA: 0x7594617430
	private Effect get_endEffect() { }
	// RVA: 0x1fff548 VA: 0x7594617548
	public Entity get_startPointOwner() { }
	// RVA: 0x1fff5c8 VA: 0x75946175c8
	public Void set_startPointOwner(Entity value) { }
	// RVA: 0x1fff670 VA: 0x7594617670
	public Entity get_endPointOwner() { }
	// RVA: 0x1fff6f0 VA: 0x75946176f0
	public Void set_endPointOwner(Entity value) { }
	// RVA: 0x1fff798 VA: 0x7594617798
	public override Void OnPlay() { }
	// RVA: 0x1fffa98 VA: 0x7594617a98
	private Void Update() { }
	// RVA: 0x1fffb78 VA: 0x7594617b78
	private Boolean _TryDestroyIfOwnerNotExist() { }
	// RVA: 0x1fffcc0 VA: 0x7594617cc0
	private Boolean _TryDestroyIfOwnerNotAliveOrReborn() { }
	// RVA: 0x1fffe08 VA: 0x7594617e08
	private Boolean _TryDestroyIfBuffNotExist() { }
	// RVA: 0x1ffffd4 VA: 0x7594617fd4
	private Void _PauseIfDisappear() { }
	// RVA: 0x20002e8 VA: 0x75946182e8
	private Void _FetchStartEndViaBuff() { }
	// RVA: 0x200083c VA: 0x759461883c
	private Void _TryUpdateEffects() { }
	// RVA: 0x20010e0 VA: 0x75946190e0
	private Void _RefreshMidPositions() { }
	// RVA: 0x20015a4 VA: 0x75946195a4
	public override Void OnFinish() { }
	// RVA: 0x20017f4 VA: 0x75946197f4
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x20019dc VA: 0x75946199dc
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x2000424 VA: 0x7594618424
	private Void _UpdateMountPoint() { }
	// RVA: 0x2001a54 VA: 0x7594619a54
	public Void .ctor() { }
	// RVA: 0x2001b7c VA: 0x7594619b7c
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2001b80 VA: 0x7594619b80
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```