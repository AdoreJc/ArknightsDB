# AVGBattleEffectPanel

**Namespace:** `Torappu.AVG`


## Fields

- `RectTransform _effectContainer`

- `ParticleEffect m_cachedImgEffect`


## Methods

- `Void _ClearAllSeq()`

- `Void _ClearAllBgEffect()`

- `Void _TryRemoveBgEffectWithLayer(Int32, Single)`

- `Boolean _ExecuteEffect(Command)`

- `Boolean _EffectMove(Vector2)`

- `ParticleEffect _TryGenEffect(ParticleEffect, Vector2, Vector3, Single, Int32)`

- `Void _TryParseRotation(EEffectFlip, ref)`

- `Boolean _ExcuteBgEffect(Command)`

- `ParticleEffect _GenEffect(ParticleEffect, Vector2, Vector3, Int32)`

- `Boolean _ExcuteImageEffect(Command)`

- `ParticleEffect _GenImgEffect(ParticleEffect, String, Vector2, Int32)`

- `AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector()`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGBattleEffectPanel : ExecutorComponent, IContainsResRefs
{
	private RectTransform _effectContainer; // 0x50
	private const Int32 MAX_EFFECT_LAYER; // 0x0
	private List`1 m_sequences; // 0x58
	private Dictionary`2 m_bgEffects; // 0x60
	private ParticleEffect m_cachedImgEffect; // 0x68
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0__ClearAllSeq; // 0x10
	private static DelegateBridge __Hotfix0__ClearAllBgEffect; // 0x18
	private static DelegateBridge __Hotfix0__TryRemoveBgEffectWithLayer; // 0x20
	private static DelegateBridge __Hotfix0__ExecuteEffect; // 0x28
	private static DelegateBridge __Hotfix0__EffectMove; // 0x30
	private static DelegateBridge __Hotfix0__TryGenEffect; // 0x38
	private static DelegateBridge __Hotfix0__TryParseRotation; // 0x40
	private static DelegateBridge __Hotfix0__ExcuteBgEffect; // 0x48
	private static DelegateBridge __Hotfix0__GenEffect; // 0x50
	private static DelegateBridge __Hotfix0__ExcuteImageEffect; // 0x58
	private static DelegateBridge __Hotfix0__GenImgEffect; // 0x60
	private static DelegateBridge __Hotfix0__OnClicked; // 0x68
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x70
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x3e5ef38 VA: 0x7596476f38
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e5f12c VA: 0x759647712c
	public override Void OnReset() { }
	// RVA: 0x3e5f1b4 VA: 0x75964771b4
	private Void _ClearAllSeq() { }
	// RVA: 0x3e5f2b0 VA: 0x75964772b0
	private Void _ClearAllBgEffect() { }
	// RVA: 0x3e5f358 VA: 0x7596477358
	private Void _TryRemoveBgEffectWithLayer(Int32 layer, Single fadeTime) { }
	// RVA: 0x3e5f554 VA: 0x7596477554
	protected Boolean _ExecuteEffect(Command command) { }
	// RVA: 0x3e5ffe8 VA: 0x7596477fe8
	private Boolean _EffectMove(Vector2 posTo) { }
	// RVA: 0x3e600cc VA: 0x75964780cc
	private ParticleEffect _TryGenEffect(ParticleEffect effect, Vector2 posVal, Vector3 rotatVal, Single duration, Int32 layer) { }
	// RVA: 0x3e5fe68 VA: 0x7596477e68
	private Void _TryParseRotation(EEffectFlip flip, ref Vector3 rotation) { }
	// RVA: 0x3e6057c VA: 0x759647857c
	protected Boolean _ExcuteBgEffect(Command command) { }
	// RVA: 0x3e60460 VA: 0x7596478460
	private ParticleEffect _GenEffect(ParticleEffect prefab, Vector2 pos, Vector3 rotate, Int32 layer) { }
	// RVA: 0x3e60e24 VA: 0x7596478e24
	protected Boolean _ExcuteImageEffect(Command command) { }
	// RVA: 0x3e61398 VA: 0x7596479398
	private ParticleEffect _GenImgEffect(ParticleEffect prefab, String imageName, Vector2 pos, Int32 layer) { }
	// RVA: 0x3e61880 VA: 0x7596479880
	protected virtual Void _OnClicked(Object arg) { }
	// RVA: 0x3e61964 VA: 0x7596479964
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e619c8 VA: 0x75964799c8
	public AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e61a5c VA: 0x7596479a5c
	public Void .ctor() { }
	// RVA: 0x3e61b6c VA: 0x7596479b6c
	private Void <>xLuaBaseProxy_OnReset() { }
}
```