# MeshAnimator

**Namespace:** `Torappu.Battle`


## Fields

- `Animation _animation`

- `Transform _muzzleTransform`

- `Transform _hitTransform`

- `Transform _headTransform`

- `Transform _graphicFootTransform`

- `Transform _specialPoint0`

- `Transform _specialPoint1`

- `Transform _specialPoint2`

- `Transform _specialPoint3`

- `Transform _specialPoint4`

- `Transform _specialPoint5`

- `Transform _specialPoint6`

- `Transform _specialPoint7`

- `Transform _specialPoint8`

- `Transform _specialPoint9`

- `Transform _specialPoint10`

- `Transform _specialPoint11`

- `Transform _specialPoint12`

- `Transform _specialPoint13`

- `Transform _specialPoint14`

- `Transform _specialPoint15`

- `Boolean _enableShowDamageFlash`

- `Boolean _enableRotate`

- `Boolean _rotateMeshOnly`

- `Transform _meshTransform`

- `Boolean _useMaterialTintColorAsDefaultColor`

- `Boolean _fixedTweenEndColor`

- `Boolean _hitTransformStable`

- `Boolean _enableThemeTintColor`

- `Boolean _checkMissing`

- `CharacterSkinHooker m_skinHooker`

- `Color m_defaultColor`

- `Boolean m_initDataFlag`

- `Tween m_lastTween`

- `Material m_material`

- `CurrentAniState m_currentAniState`


## Properties

- `Boolean enableRotate`

- `Boolean rotateMeshOnly`

- `Renderer renderer`


## Methods

- `Boolean get_enableRotate()`

- `Boolean get_rotateMeshOnly()`

- `Renderer get_renderer()`

- `Single PlayAnimation(AnimationData, Boolean, Single)`

- `AnimationData GetAnimationData(String, Boolean)`

- `Void InitAnimationDataIfNot()`

- `Void UpdateAnimationData(Boolean)`

- `Void _InitRenderersIfNot()`

- `CharacterSkinHooker <>xLuaBaseProxy_get_skinHooker()`

- `Transform <>xLuaBaseProxy_get_graphicFootTransform()`

- `Void <>xLuaBaseProxy_Init(Unit)`

- `Void <>xLuaBaseProxy_EnableVisualPart(Boolean)`

- `Void <>xLuaBaseProxy_DoResetColor(UnitAnimator)`

- `Void <>xLuaBaseProxy_OnFinish()`

- `Transform <>xLuaBaseProxy_GetMountPoint(MountPointType)`

- `Boolean <>xLuaBaseProxy_TryHookEffect(String, out)`

- `Void <>xLuaBaseProxy_Awake()`

- `Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MeshAnimator : UnitAnimator
{
	private Animation _animation; // 0x40
	private Transform _muzzleTransform; // 0x48
	private Transform _hitTransform; // 0x50
	private Transform _headTransform; // 0x58
	private Transform _graphicFootTransform; // 0x60
	private Transform _specialPoint0; // 0x68
	private Transform _specialPoint1; // 0x70
	private Transform _specialPoint2; // 0x78
	private Transform _specialPoint3; // 0x80
	private Transform _specialPoint4; // 0x88
	private Transform _specialPoint5; // 0x90
	private Transform _specialPoint6; // 0x98
	private Transform _specialPoint7; // 0xa0
	private Transform _specialPoint8; // 0xa8
	private Transform _specialPoint9; // 0xb0
	private Transform _specialPoint10; // 0xb8
	private Transform _specialPoint11; // 0xc0
	private Transform _specialPoint12; // 0xc8
	private Transform _specialPoint13; // 0xd0
	private Transform _specialPoint14; // 0xd8
	private Transform _specialPoint15; // 0xe0
	private AnimationData[] _animations; // 0xe8
	private Boolean _enableShowDamageFlash; // 0xf0
	private Boolean _enableRotate; // 0xf1
	private Boolean _rotateMeshOnly; // 0xf2
	private Transform _meshTransform; // 0xf8
	private Boolean _useMaterialTintColorAsDefaultColor; // 0x100
	private Boolean _fixedTweenEndColor; // 0x101
	private Renderer[] _constRenders; // 0x108
	private Boolean _hitTransformStable; // 0x110
	private Boolean _enableThemeTintColor; // 0x111
	private Boolean _checkMissing; // 0x112
	private CharacterSkinHooker m_skinHooker; // 0x118
	private Color m_defaultColor; // 0x120
	private Renderer[] m_renderers; // 0x130
	private Boolean m_initDataFlag; // 0x138
	private Dictionary`2 m_animationDict; // 0x140
	private Tween m_lastTween; // 0x148
	private Material m_material; // 0x150
	private CurrentAniState m_currentAniState; // 0x158
	private static DelegateBridge __Hotfix0_get_skinHooker; // 0x0
	private static DelegateBridge __Hotfix0_get_color; // 0x8
	private static DelegateBridge __Hotfix0_set_color; // 0x10
	private static DelegateBridge __Hotfix0_get_enableRotate; // 0x18
	private static DelegateBridge __Hotfix0_get_rotateMeshOnly; // 0x20
	private static DelegateBridge __Hotfix0_get_graphicTransform; // 0x28
	private static DelegateBridge __Hotfix0_get_muzzleTransform; // 0x30
	private static DelegateBridge __Hotfix0_get_hitTransform; // 0x38
	private static DelegateBridge __Hotfix0_get_footTransform; // 0x40
	private static DelegateBridge __Hotfix0_get_graphicFootTransform; // 0x48
	private static DelegateBridge __Hotfix0_get_headTransform; // 0x50
	private static DelegateBridge __Hotfix0_get_shadowTransform; // 0x58
	private static DelegateBridge __Hotfix0_get_renderer; // 0x60
	private static DelegateBridge __Hotfix0_get_animation; // 0x68
	private static DelegateBridge __Hotfix0_get_animations; // 0x70
	private static DelegateBridge __Hotfix0_Init; // 0x78
	private static DelegateBridge __Hotfix0_EnableVisualPart; // 0x80
	private static DelegateBridge __Hotfix0_GetCurrentAniState; // 0x88
	private static DelegateBridge __Hotfix0_DoResetColor; // 0x90
	private static DelegateBridge __Hotfix0_Stop; // 0x98
	private static DelegateBridge __Hotfix0_PlayAnimationInternal; // 0xa0
	private static DelegateBridge __Hotfix0_ContainsAnimationInternal; // 0xa8
	private static DelegateBridge __Hotfix0_GetAnimationTimeInternal; // 0xb0
	private static DelegateBridge __Hotfix1_GetAnimationTimeInternal; // 0xb8
	private static DelegateBridge __Hotfix0_OnTakeDamage; // 0xc0
	private static DelegateBridge __Hotfix0_OnFinish; // 0xc8
	private static DelegateBridge __Hotfix0_GetMountPoint; // 0xd0
	private static DelegateBridge __Hotfix0_TryHookEffect; // 0xd8
	private static DelegateBridge __Hotfix0_Awake; // 0xe0
	private static DelegateBridge __Hotfix0_PlayAnimation; // 0xe8
	private static DelegateBridge __Hotfix0_GetAnimationData; // 0xf0
	private static DelegateBridge __Hotfix0_InitAnimationDataIfNot; // 0xf8
	private static DelegateBridge __Hotfix0_UpdateAnimationData; // 0x100
	private static DelegateBridge __Hotfix0_DoUpdateFaceSign; // 0x108
	private static DelegateBridge __Hotfix0__InitRenderersIfNot; // 0x110
	private static DelegateBridge __Hotfix0_OnFaceChanged; // 0x118
	private static DelegateBridge _c__Hotfix0_ctor; // 0x120

	public override CharacterSkinHooker skinHooker { get; }
	public override Color color { get; set; }
	protected Boolean enableRotate { get; }
	protected Boolean rotateMeshOnly { get; }
	public override Transform graphicTransform { get; }
	protected override Transform muzzleTransform { get; }
	public override Transform hitTransform { get; }
	public override Transform footTransform { get; }
	public override Transform graphicFootTransform { get; }
	public override Transform headTransform { get; }
	public override Transform shadowTransform { get; }
	protected Renderer renderer { get; }
	protected virtual Animation animation { get; }
	protected AnimationData[] animations { get; }

	// RVA: 0x3f2f6cc VA: 0x75965476cc
	public override CharacterSkinHooker get_skinHooker() { }
	// RVA: 0x3f2f734 VA: 0x7596547734
	public override Color get_color() { }
	// RVA: 0x3f2f810 VA: 0x7596547810
	public override Void set_color(Color value) { }
	// RVA: 0x3f2fd20 VA: 0x7596547d20
	protected Boolean get_enableRotate() { }
	// RVA: 0x3f2fd88 VA: 0x7596547d88
	protected Boolean get_rotateMeshOnly() { }
	// RVA: 0x3f2fe08 VA: 0x7596547e08
	public override Transform get_graphicTransform() { }
	// RVA: 0x3f2fe74 VA: 0x7596547e74
	protected override Transform get_muzzleTransform() { }
	// RVA: 0x3f2ff34 VA: 0x7596547f34
	public override Transform get_hitTransform() { }
	// RVA: 0x3f30068 VA: 0x7596548068
	public override Transform get_footTransform() { }
	// RVA: 0x3f30168 VA: 0x7596548168
	public override Transform get_graphicFootTransform() { }
	// RVA: 0x3f30220 VA: 0x7596548220
	public override Transform get_headTransform() { }
	// RVA: 0x3f302e0 VA: 0x75965482e0
	public override Transform get_shadowTransform() { }
	// RVA: 0x3f300e0 VA: 0x75965480e0
	protected Renderer get_renderer() { }
	// RVA: 0x3f30354 VA: 0x7596548354
	protected virtual Animation get_animation() { }
	// RVA: 0x3f303bc VA: 0x75965483bc
	protected AnimationData[] get_animations() { }
	// RVA: 0x3f30424 VA: 0x7596548424
	public override Void Init(Unit host) { }
	// RVA: 0x3f305a0 VA: 0x75965485a0
	public override Void EnableVisualPart(Boolean enable) { }
	// RVA: 0x3f30668 VA: 0x7596548668
	public override CurrentAniState GetCurrentAniState() { }
	// RVA: 0x3f306cc VA: 0x75965486cc
	protected override Void DoResetColor(UnitAnimator oldAnimator) { }
	// RVA: 0x3f307b0 VA: 0x75965487b0
	public override Void Stop() { }
	// RVA: 0x3f30894 VA: 0x7596548894
	protected override Single PlayAnimationInternal(String animKey, Boolean forceFromStart, Single speed) { }
	// RVA: 0x3f30c9c VA: 0x7596548c9c
	protected override Boolean ContainsAnimationInternal(String animKey, Boolean allowEmpty) { }
	// RVA: 0x3f30d64 VA: 0x7596548d64
	protected override Boolean GetAnimationTimeInternal(String animKey, out Single time) { }
	// RVA: 0x3f30e10 VA: 0x7596548e10
	protected override Boolean GetAnimationTimeInternal(String animKey, out Single time, out Single speed) { }
	// RVA: 0x3f30edc VA: 0x7596548edc
	public override Void OnTakeDamage(ref Modifier modifier) { }
	// RVA: 0x3f311fc VA: 0x75965491fc
	public override Void OnFinish() { }
	// RVA: 0x3f312d8 VA: 0x75965492d8
	public override Transform GetMountPoint(MountPointType mountPointType) { }
	// RVA: 0x3f3145c VA: 0x759654945c
	public override Boolean TryHookEffect(String originEffectKey, out String newEffectKey) { }
	// RVA: 0x3f3155c VA: 0x759654955c
	protected override Void Awake() { }
	// RVA: 0x3f30a18 VA: 0x7596548a18
	protected Single PlayAnimation(AnimationData data, Boolean forceFromStart, Single speed) { }
	// RVA: 0x3f30948 VA: 0x7596548948
	protected AnimationData GetAnimationData(String animKey, Boolean ignoreInvalid) { }
	// RVA: 0x3f304b0 VA: 0x75965484b0
	protected Void InitAnimationDataIfNot() { }
	// RVA: 0x3f315f8 VA: 0x75965495f8
	protected Void UpdateAnimationData(Boolean checkMissing) { }
	// RVA: 0x3f31938 VA: 0x7596549938
	protected override Void DoUpdateFaceSign(Int32 faceSign) { }
	// RVA: 0x3f2f93c VA: 0x759654793c
	private Void _InitRenderersIfNot() { }
	// RVA: 0x3f319b0 VA: 0x75965499b0
	public override Void OnFaceChanged(Vector2 newDir, Vector2 oldDir, Boolean force, Boolean isIdle) { }
	// RVA: 0x3f31b78 VA: 0x7596549b78
	public Void .ctor() { }
	// RVA: 0x3f31cbc VA: 0x7596549cbc
	private CharacterSkinHooker <>xLuaBaseProxy_get_skinHooker() { }
	// RVA: 0x3f31cc4 VA: 0x7596549cc4
	private Transform <>xLuaBaseProxy_get_graphicFootTransform() { }
	// RVA: 0x3f31ccc VA: 0x7596549ccc
	private Void <>xLuaBaseProxy_Init(Unit P0) { }
	// RVA: 0x3f31cd4 VA: 0x7596549cd4
	private Void <>xLuaBaseProxy_EnableVisualPart(Boolean P0) { }
	// RVA: 0x3f31ce0 VA: 0x7596549ce0
	private Void <>xLuaBaseProxy_DoResetColor(UnitAnimator P0) { }
	// RVA: 0x3f31ce8 VA: 0x7596549ce8
	private Void <>xLuaBaseProxy_OnFinish() { }
	// RVA: 0x3f31cf0 VA: 0x7596549cf0
	private Transform <>xLuaBaseProxy_GetMountPoint(MountPointType P0) { }
	// RVA: 0x3f31cf8 VA: 0x7596549cf8
	private Boolean <>xLuaBaseProxy_TryHookEffect(String P0, out String P1) { }
	// RVA: 0x3f31d00 VA: 0x7596549d00
	private Void <>xLuaBaseProxy_Awake() { }
	// RVA: 0x3f31d08 VA: 0x7596549d08
	private Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32 P0) { }
}
```