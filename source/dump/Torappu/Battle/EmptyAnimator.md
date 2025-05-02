# EmptyAnimator

**Namespace:** `Torappu.Battle`


## Fields

- `Transform _hitTransform`

- `Transform _headTransform`

- `Transform _muzzle`


## Properties

- `Boolean enableWhiteList`


## Methods

- `Boolean get_enableWhiteList()`

- `Int32 <>xLuaBaseProxy_get_faceSign()`

- `Boolean <>xLuaBaseProxy_TryIgnoreEffect(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EmptyAnimator : UnitAnimator
{
	private Transform _hitTransform; // 0x40
	private Transform _headTransform; // 0x48
	private Transform _muzzle; // 0x50
	private List`1 _effectWhiteList; // 0x58
	private static DelegateBridge __Hotfix0_get_color; // 0x0
	private static DelegateBridge __Hotfix0_set_color; // 0x8
	private static DelegateBridge __Hotfix0_get_faceSign; // 0x10
	private static DelegateBridge __Hotfix0_get_enableWhiteList; // 0x18
	private static DelegateBridge __Hotfix0_get_effectWhiteList; // 0x20
	private static DelegateBridge __Hotfix0_get_graphicTransform; // 0x28
	private static DelegateBridge __Hotfix0_get_muzzleTransform; // 0x30
	private static DelegateBridge __Hotfix0_get_hitTransform; // 0x38
	private static DelegateBridge __Hotfix0_get_footTransform; // 0x40
	private static DelegateBridge __Hotfix0_get_headTransform; // 0x48
	private static DelegateBridge __Hotfix0_get_shadowTransform; // 0x50
	private static DelegateBridge __Hotfix0_Stop; // 0x58
	private static DelegateBridge __Hotfix0_PlayAnimationInternal; // 0x60
	private static DelegateBridge __Hotfix0_ContainsAnimationInternal; // 0x68
	private static DelegateBridge __Hotfix0_GetAnimationTimeInternal; // 0x70
	private static DelegateBridge __Hotfix1_GetAnimationTimeInternal; // 0x78
	private static DelegateBridge __Hotfix0_OnFaceChanged; // 0x80
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0x88
	private static DelegateBridge __Hotfix0_GetCurrentAniState; // 0x90
	private static DelegateBridge __Hotfix0_TryIgnoreEffect; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public override Color color { get; set; }
	public override Int32 faceSign { get; }
	public Boolean enableWhiteList { get; }
	public List`1 effectWhiteList { get; }
	public override Transform graphicTransform { get; }
	protected override Transform muzzleTransform { get; }
	public override Transform hitTransform { get; }
	public override Transform footTransform { get; }
	public override Transform headTransform { get; }
	public override Transform shadowTransform { get; }

	// RVA: 0x3f2dbac VA: 0x7596545bac
	public override Color get_color() { }
	// RVA: 0x3f2dc1c VA: 0x7596545c1c
	public override Void set_color(Color value) { }
	// RVA: 0x3f2dcb8 VA: 0x7596545cb8
	public override Int32 get_faceSign() { }
	// RVA: 0x3f2dd20 VA: 0x7596545d20
	public Boolean get_enableWhiteList() { }
	// RVA: 0x3f2ddb0 VA: 0x7596545db0
	public List`1 get_effectWhiteList() { }
	// RVA: 0x3f2de18 VA: 0x7596545e18
	public override Transform get_graphicTransform() { }
	// RVA: 0x3f2de84 VA: 0x7596545e84
	protected override Transform get_muzzleTransform() { }
	// RVA: 0x3f2df3c VA: 0x7596545f3c
	public override Transform get_hitTransform() { }
	// RVA: 0x3f2dff4 VA: 0x7596545ff4
	public override Transform get_footTransform() { }
	// RVA: 0x3f2e060 VA: 0x7596546060
	public override Transform get_headTransform() { }
	// RVA: 0x3f2e118 VA: 0x7596546118
	public override Transform get_shadowTransform() { }
	// RVA: 0x3f2e184 VA: 0x7596546184
	public override Void Stop() { }
	// RVA: 0x3f2e1e8 VA: 0x75965461e8
	protected override Single PlayAnimationInternal(String animKey, Boolean forceFromStart, Single speed) { }
	// RVA: 0x3f2e280 VA: 0x7596546280
	protected override Boolean ContainsAnimationInternal(String animKey, Boolean allowEmpty) { }
	// RVA: 0x3f2e300 VA: 0x7596546300
	protected override Boolean GetAnimationTimeInternal(String animKey, out Single time) { }
	// RVA: 0x3f2e384 VA: 0x7596546384
	protected override Boolean GetAnimationTimeInternal(String animKey, out Single time, out Single speed) { }
	// RVA: 0x3f2e424 VA: 0x7596546424
	public override Void OnFaceChanged(Vector2 newDir, Vector2 oldDir, Boolean force, Boolean isIdle) { }
	// RVA: 0x3f2e4dc VA: 0x75965464dc
	public override Void OnTakeDamage(ref Modifier modifier) { }
	// RVA: 0x3f2e554 VA: 0x7596546554
	public override CurrentAniState GetCurrentAniState() { }
	// RVA: 0x3f2e5b8 VA: 0x75965465b8
	public override Boolean TryIgnoreEffect(String originEffectKey) { }
	// RVA: 0x3f2e68c VA: 0x759654668c
	public Void .ctor() { }
	// RVA: 0x3f2e6fc VA: 0x75965466fc
	private Int32 <>xLuaBaseProxy_get_faceSign() { }
	// RVA: 0x3f2e704 VA: 0x7596546704
	private Boolean <>xLuaBaseProxy_TryIgnoreEffect(String P0) { }
}
```