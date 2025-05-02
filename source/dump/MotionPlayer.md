# MotionPlayer

**Namespace:** ` `


## Fields

- `RecruitImage m_bkg`

- `Int32 m_index`

- `GameObject m_gameObject`


## Methods

- `Void Init(Int32, RecruitGachaItemViewBase)`

- `Void OnDragStateChanged(Single)`

- `Void PlayerInitialMotionEffect()`

- `Void _ApplyDragImageBias(Single)`

- `Void _ApplyEffectImageBias(Single)`

- `Void OnDisable()`

- `Void _CancelPrevMotionEffects(Boolean)`

- `Boolean _IsEffectTweening()`

- `Void _InitMotionList(RecruitGachaItemViewBase)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class MotionPlayer : IHotfixable
{
	private const Single INIT_EFFECT_DELAY; // 0x0
	private const Single INIT_EFFECT_MOVE_DUR; // 0x0
	private const Single INIT_EFFECT_FADE_DUR; // 0x0
	private const Single INIT_EFFECT_BIAS; // 0x0
	private const Single INIT_EFFECT_BASE_DELTA; // 0x0
	private const Single INIT_EFFECT_MOVE_SCALE; // 0x0
	private List`1 m_images; // 0x10
	private RecruitImage m_bkg; // 0x18
	private Int32 m_index; // 0x20
	private List`1 m_tweens; // 0x28
	private GameObject m_gameObject; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnDragStateChanged; // 0x8
	private static DelegateBridge __Hotfix0_PlayerInitialMotionEffect; // 0x10
	private static DelegateBridge __Hotfix0__ApplyDragImageBias; // 0x18
	private static DelegateBridge __Hotfix0__ApplyEffectImageBias; // 0x20
	private static DelegateBridge __Hotfix0_OnDisable; // 0x28
	private static DelegateBridge __Hotfix0__CancelPrevMotionEffects; // 0x30
	private static DelegateBridge __Hotfix0__IsEffectTweening; // 0x38
	private static DelegateBridge __Hotfix0__InitMotionList; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x27189a0 VA: 0x7594d309a0
	public Void Init(Int32 index, RecruitGachaItemViewBase closure) { }
	// RVA: 0x2717cdc VA: 0x7594d2fcdc
	public Void OnDragStateChanged(Single state) { }
	// RVA: 0x2717df8 VA: 0x7594d2fdf8
	public Void PlayerInitialMotionEffect() { }
	// RVA: 0x2718f88 VA: 0x7594d30f88
	private Void _ApplyDragImageBias(Single bias) { }
	// RVA: 0x27190f4 VA: 0x7594d310f4
	private Void _ApplyEffectImageBias(Single bias) { }
	// RVA: 0x2717be8 VA: 0x7594d2fbe8
	public Void OnDisable() { }
	// RVA: 0x2718e74 VA: 0x7594d30e74
	private Void _CancelPrevMotionEffects(Boolean resetToTarget) { }
	// RVA: 0x2719284 VA: 0x7594d31284
	private Boolean _IsEffectTweening() { }
	// RVA: 0x2718b7c VA: 0x7594d30b7c
	private Void _InitMotionList(RecruitGachaItemViewBase closure) { }
	// RVA: 0x2718a50 VA: 0x7594d30a50
	public Void .ctor() { }
}
```