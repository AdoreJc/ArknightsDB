# OnPlayEmitter

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _instant`

- `Single _preDelay`

- `Boolean _useFaceVector`

- `Boolean _clearWhenFinish`

- `Boolean _keepPauseSync`


## Properties

- `Boolean instant`


## Methods

- `Boolean get_instant()`

- `Void _OnPlayInternal()`

- `Void GatherEffects(List`1)`

- `IEnumerator _DoEmitWithPreDelay()`

- `Void _DoEmit()`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_Init(Effect)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Void <>xLuaBaseProxy_OnPaused(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class OnPlayEmitter : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String[] _effects; // 0x20
	private Boolean _instant; // 0x28
	private Single _preDelay; // 0x2c
	private Boolean _useFaceVector; // 0x30
	private Boolean _clearWhenFinish; // 0x31
	private Boolean _keepPauseSync; // 0x32
	private List`1 m_effects; // 0x38
	private static DelegateBridge __Hotfix0_get_instant; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnPlay; // 0x10
	private static DelegateBridge __Hotfix0__OnPlayInternal; // 0x18
	private static DelegateBridge __Hotfix0_OnFinish; // 0x20
	private static DelegateBridge __Hotfix0_OnPaused; // 0x28
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x30
	private static DelegateBridge __Hotfix0__DoEmitWithPreDelay; // 0x38
	private static DelegateBridge __Hotfix0__DoEmit; // 0x40
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Boolean instant { get; }

	// RVA: 0x2002534 VA: 0x759461a534
	private Boolean get_instant() { }
	// RVA: 0x200259c VA: 0x759461a59c
	public override Void Init(Effect effect) { }
	// RVA: 0x2002688 VA: 0x759461a688
	public override Void OnPlay() { }
	// RVA: 0x20026f0 VA: 0x759461a6f0
	protected Void _OnPlayInternal() { }
	// RVA: 0x2002b08 VA: 0x759461ab08
	public override Void OnFinish() { }
	// RVA: 0x2002b90 VA: 0x759461ab90
	public override Void OnPaused(Boolean paused) { }
	// RVA: 0x2002d8c VA: 0x759461ad8c
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x2002a5c VA: 0x759461aa5c
	private IEnumerator _DoEmitWithPreDelay() { }
	// RVA: 0x2002780 VA: 0x759461a780
	private Void _DoEmit() { }
	// RVA: 0x2002e68 VA: 0x759461ae68
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x2002ee0 VA: 0x759461aee0
	public Void .ctor() { }
	// RVA: 0x2002f4c VA: 0x759461af4c
	private Void <>xLuaBaseProxy_Init(Effect P0) { }
	// RVA: 0x2002f50 VA: 0x759461af50
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2002f54 VA: 0x759461af54
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x2002f58 VA: 0x759461af58
	private Void <>xLuaBaseProxy_OnPaused(Boolean P0) { }
}
```