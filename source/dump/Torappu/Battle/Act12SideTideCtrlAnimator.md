# Act12SideTideCtrlAnimator

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean m_hasAnimation`

- `Animation m_sceneAnimation`

- `Boolean m_animationInit`

- `String m_cachedAnimationKey`

- `CoroutineId m_transitionCoroutine`


## Methods

- `Boolean _InitSceneAnimation()`

- `Void _CacheFirstAnimation()`

- `IEnumerator _PlayCrossFadeAnimation(AnimationData, AnimationData, Boolean, Single)`

- `AnimationTransitionData _GetTransitionData(String, String)`

- `Animation <>xLuaBaseProxy_get_animation()`

- `Void <>xLuaBaseProxy_Init(Unit)`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Boolean <>xLuaBaseProxy_ContainsAnimationInternal(String, Boolean)`

- `Boolean <>xLuaBaseProxy_GetAnimationTimeInternal(String, out)`

- `Boolean <>xLuaBaseProxy_GetAnimationTimeInternal(String, out, out)`

- `Single <>xLuaBaseProxy_PlayAnimationInternal(String, Boolean, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act12SideTideCtrlAnimator : MeshAnimator
{
	private AnimationTransitionData[] _transitions; // 0x168
	private Boolean m_hasAnimation; // 0x170
	private Animation m_sceneAnimation; // 0x178
	private Boolean m_animationInit; // 0x180
	private String m_cachedAnimationKey; // 0x188
	private CoroutineId m_transitionCoroutine; // 0x190
	private static DelegateBridge __Hotfix0_get_animation; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0__InitSceneAnimation; // 0x18
	private static DelegateBridge __Hotfix0__CacheFirstAnimation; // 0x20
	private static DelegateBridge __Hotfix0_ContainsAnimationInternal; // 0x28
	private static DelegateBridge __Hotfix0_GetAnimationTimeInternal; // 0x30
	private static DelegateBridge __Hotfix1_GetAnimationTimeInternal; // 0x38
	private static DelegateBridge __Hotfix0_PlayAnimationInternal; // 0x40
	private static DelegateBridge __Hotfix0__PlayCrossFadeAnimation; // 0x48
	private static DelegateBridge __Hotfix0__GetTransitionData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected override Animation animation { get; }

	// RVA: 0x3f365a4 VA: 0x759654e5a4
	protected override Animation get_animation() { }
	// RVA: 0x3f3660c VA: 0x759654e60c
	public override Void Init(Unit host) { }
	// RVA: 0x3f3688c VA: 0x759654e88c
	public override Void OnFinish() { }
	// RVA: 0x3f366a0 VA: 0x759654e6a0
	private Boolean _InitSceneAnimation() { }
	// RVA: 0x3f36974 VA: 0x759654e974
	private Void _CacheFirstAnimation() { }
	// RVA: 0x3f36ab8 VA: 0x759654eab8
	protected override Boolean ContainsAnimationInternal(String animKey, Boolean allowEmpty) { }
	// RVA: 0x3f36b60 VA: 0x759654eb60
	protected override Boolean GetAnimationTimeInternal(String animKey, out Single time) { }
	// RVA: 0x3f36c0c VA: 0x759654ec0c
	protected override Boolean GetAnimationTimeInternal(String animKey, out Single time, out Single speed) { }
	// RVA: 0x3f36cdc VA: 0x759654ecdc
	protected override Single PlayAnimationInternal(String animKey, Boolean forceFromStart, Single speed) { }
	// RVA: 0x3f3704c VA: 0x759654f04c
	private IEnumerator _PlayCrossFadeAnimation(AnimationData transitionAnim, AnimationData animData, Boolean forceFromStart, Single speed) { }
	// RVA: 0x3f36f2c VA: 0x759654ef2c
	private AnimationTransitionData _GetTransitionData(String from, String to) { }
	// RVA: 0x3f37168 VA: 0x759654f168
	public Void .ctor() { }
	// RVA: 0x3f37210 VA: 0x759654f210
	private Animation <>xLuaBaseProxy_get_animation() { }
	// RVA: 0x3f37214 VA: 0x759654f214
	private Void <>xLuaBaseProxy_Init(Unit P0) { }
	// RVA: 0x3f37218 VA: 0x759654f218
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x3f3721c VA: 0x759654f21c
	private Boolean <>xLuaBaseProxy_ContainsAnimationInternal(String P0, Boolean P1) { }
	// RVA: 0x3f37224 VA: 0x759654f224
	private Boolean <>xLuaBaseProxy_GetAnimationTimeInternal(String P0, out Single P1) { }
	// RVA: 0x3f37228 VA: 0x759654f228
	private Boolean <>xLuaBaseProxy_GetAnimationTimeInternal(String P0, out Single P1, out Single P2) { }
	// RVA: 0x3f3722c VA: 0x759654f22c
	private Single <>xLuaBaseProxy_PlayAnimationInternal(String P0, Boolean P1, Single P2) { }
}
```