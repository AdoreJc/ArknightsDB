# MultiSpineAnimator

**Namespace:** `Torappu.Battle`


## Fields

- `FaceSwitcher _faceSwitcher`

- `Int32 m_activeSpineIndex`

- `Int32 nextSpineIndex`

- `Color m_color`

- `String m_currentAnimKey`


## Properties

- `SubSpineConfig activeFace`

- `Int32 activeSpineIndex`


## Methods

- `SubSpineConfig get_activeFace()`

- `Int32 get_activeSpineIndex()`

- `Void SwitchSpine(Int32)`

- `Void SwitchNextSpine()`

- `Void _SwapConfiguration(Int32, Boolean, Boolean)`

- `Void _SyncAnimationState(SubSpineConfig, SubSpineConfig)`

- `Void _ResetSkeletonToDefaultPose(SubSpineConfig)`

- `Void _UpdateDirection(Direction, Direction)`

- `Color <>xLuaBaseProxy_get_color()`

- `Void <>xLuaBaseProxy_set_color(Color)`

- `Transform <>xLuaBaseProxy_GetMountPoint(MountPointType)`

- `Void <>xLuaBaseProxy_Init(Unit)`

- `Void <>xLuaBaseProxy_OnReset(UnitAnimator)`

- `Void <>xLuaBaseProxy_InitAnimationDataIfNot()`

- `Void <>xLuaBaseProxy_UpdateAnimationData(Boolean)`

- `AnimationData <>xLuaBaseProxy_GetAnimationData(String, Boolean)`

- `Single <>xLuaBaseProxy_PlayAnimationInternal(String, Boolean, Single)`

- `Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MultiSpineAnimator : SpineAnimator
{
	private List`1 _faces; // 0xd8
	private FaceSwitcher _faceSwitcher; // 0xe0
	private Int32 m_activeSpineIndex; // 0xe8
	public Int32 nextSpineIndex; // 0xec
	private Color m_color; // 0xf0
	private Action`2 m_updateDir; // 0x100
	private String m_currentAnimKey; // 0x108
	private static DelegateBridge __Hotfix0_get_activeFace; // 0x0
	private static DelegateBridge __Hotfix0_get_faces; // 0x8
	private static DelegateBridge __Hotfix0_get_activeSpineIndex; // 0x10
	private static DelegateBridge __Hotfix0_get_color; // 0x18
	private static DelegateBridge __Hotfix0_set_color; // 0x20
	private static DelegateBridge __Hotfix0_get_skeleton; // 0x28
	private static DelegateBridge __Hotfix0_get_faceSwitcher; // 0x30
	private static DelegateBridge __Hotfix0_get_graphicTransform; // 0x38
	private static DelegateBridge __Hotfix0_get_hitTransform; // 0x40
	private static DelegateBridge __Hotfix0_get_footTransform; // 0x48
	private static DelegateBridge __Hotfix0_get_headTransform; // 0x50
	private static DelegateBridge __Hotfix0_get_shadowTransform; // 0x58
	private static DelegateBridge __Hotfix0_get_muzzleTransform; // 0x60
	private static DelegateBridge __Hotfix0_GetMountPoint; // 0x68
	private static DelegateBridge __Hotfix0_SwitchSpine; // 0x70
	private static DelegateBridge __Hotfix0_SwitchNextSpine; // 0x78
	private static DelegateBridge __Hotfix0_Init; // 0x80
	private static DelegateBridge __Hotfix0_OnReset; // 0x88
	private static DelegateBridge __Hotfix0_OnFaceChanged; // 0x90
	private static DelegateBridge __Hotfix0_InitAnimationDataIfNot; // 0x98
	private static DelegateBridge __Hotfix0_UpdateAnimationData; // 0xa0
	private static DelegateBridge __Hotfix0_GetAnimationData; // 0xa8
	private static DelegateBridge __Hotfix0_PlayAnimationInternal; // 0xb0
	private static DelegateBridge __Hotfix0_DoUpdateFaceSign; // 0xb8
	private static DelegateBridge __Hotfix0_ForEachSkeleton; // 0xc0
	private static DelegateBridge __Hotfix0__SwapConfiguration; // 0xc8
	private static DelegateBridge __Hotfix0__SyncAnimationState; // 0xd0
	private static DelegateBridge __Hotfix0__ResetSkeletonToDefaultPose; // 0xd8
	private static DelegateBridge __Hotfix0__GetAnimationData; // 0xe0
	private static DelegateBridge __Hotfix0__UpdateDirection; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	private SubSpineConfig activeFace { get; }
	public List`1 faces { get; }
	public Int32 activeSpineIndex { get; }
	public override Color color { get; set; }
	public override SkeletonAnimation skeleton { get; }
	public override FaceSwitcher faceSwitcher { get; }
	public override Transform graphicTransform { get; }
	public override Transform hitTransform { get; }
	public override Transform footTransform { get; }
	public override Transform headTransform { get; }
	public override Transform shadowTransform { get; }
	protected override Transform muzzleTransform { get; }

	// RVA: 0x3f31ea0 VA: 0x7596549ea0
	private SubSpineConfig get_activeFace() { }
	// RVA: 0x3f31f2c VA: 0x7596549f2c
	public List`1 get_faces() { }
	// RVA: 0x3f31f94 VA: 0x7596549f94
	public Int32 get_activeSpineIndex() { }
	// RVA: 0x3f31ffc VA: 0x7596549ffc
	public override Color get_color() { }
	// RVA: 0x3f32064 VA: 0x759654a064
	public override Void set_color(Color value) { }
	// RVA: 0x3f32250 VA: 0x759654a250
	public override SkeletonAnimation get_skeleton() { }
	// RVA: 0x3f322c8 VA: 0x759654a2c8
	public override FaceSwitcher get_faceSwitcher() { }
	// RVA: 0x3f32330 VA: 0x759654a330
	public override Transform get_graphicTransform() { }
	// RVA: 0x3f3239c VA: 0x759654a39c
	public override Transform get_hitTransform() { }
	// RVA: 0x3f3247c VA: 0x759654a47c
	public override Transform get_footTransform() { }
	// RVA: 0x3f324fc VA: 0x759654a4fc
	public override Transform get_headTransform() { }
	// RVA: 0x3f325dc VA: 0x759654a5dc
	public override Transform get_shadowTransform() { }
	// RVA: 0x3f326bc VA: 0x759654a6bc
	protected override Transform get_muzzleTransform() { }
	// RVA: 0x3f3279c VA: 0x759654a79c
	public override Transform GetMountPoint(MountPointType mountPointType) { }
	// RVA: 0x3f329e4 VA: 0x759654a9e4
	public Void SwitchSpine(Int32 index) { }
	// RVA: 0x3f32d84 VA: 0x759654ad84
	public Void SwitchNextSpine() { }
	// RVA: 0x3f32df0 VA: 0x759654adf0
	public override Void Init(Unit unit) { }
	// RVA: 0x3f330e0 VA: 0x759654b0e0
	public override Void OnReset(UnitAnimator old) { }
	// RVA: 0x3f3342c VA: 0x759654b42c
	public override Void OnFaceChanged(Vector2 newDir, Vector2 oldDir, Boolean force, Boolean isIdle) { }
	// RVA: 0x3f33618 VA: 0x759654b618
	protected override Void InitAnimationDataIfNot() { }
	// RVA: 0x3f338e4 VA: 0x759654b8e4
	protected override Void UpdateAnimationData(Boolean checkMissing) { }
	// RVA: 0x3f33cf8 VA: 0x759654bcf8
	protected override AnimationData GetAnimationData(String animKey, Boolean ignoreInvalid) { }
	// RVA: 0x3f33df4 VA: 0x759654bdf4
	protected override Single PlayAnimationInternal(String animKey, Boolean forceFromStart, Single speed) { }
	// RVA: 0x3f33eac VA: 0x759654beac
	protected override Void DoUpdateFaceSign(Int32 sign) { }
	// RVA: 0x3f34048 VA: 0x759654c048
	protected override Void ForEachSkeleton(Action`1 func) { }
	// RVA: 0x3f32af0 VA: 0x759654aaf0
	private Void _SwapConfiguration(Int32 toIndex, Boolean needSync, Boolean force) { }
	// RVA: 0x3f341f0 VA: 0x759654c1f0
	private Void _SyncAnimationState(SubSpineConfig toSpine, SubSpineConfig fromSpine) { }
	// RVA: 0x3f33308 VA: 0x759654b308
	private Void _ResetSkeletonToDefaultPose(SubSpineConfig spine) { }
	// RVA: 0x3f34568 VA: 0x759654c568
	private static AnimationData _GetAnimationData(String animKey, Boolean ignoreInvalid, SubSpineConfig spine) { }
	// RVA: 0x3f3463c VA: 0x759654c63c
	private Void _UpdateDirection(Direction lOrR, Direction fourDir) { }
	// RVA: 0x3f346c8 VA: 0x759654c6c8
	public Void .ctor() { }
	// RVA: 0x3f34740 VA: 0x759654c740
	private Color <>xLuaBaseProxy_get_color() { }
	// RVA: 0x3f34748 VA: 0x759654c748
	private Void <>xLuaBaseProxy_set_color(Color P0) { }
	// RVA: 0x3f34750 VA: 0x759654c750
	private Transform <>xLuaBaseProxy_GetMountPoint(MountPointType P0) { }
	// RVA: 0x3f34758 VA: 0x759654c758
	private Void <>xLuaBaseProxy_Init(Unit P0) { }
	// RVA: 0x3f34760 VA: 0x759654c760
	private Void <>xLuaBaseProxy_OnReset(UnitAnimator P0) { }
	// RVA: 0x3f34768 VA: 0x759654c768
	private Void <>xLuaBaseProxy_InitAnimationDataIfNot() { }
	// RVA: 0x3f34770 VA: 0x759654c770
	private Void <>xLuaBaseProxy_UpdateAnimationData(Boolean P0) { }
	// RVA: 0x3f3477c VA: 0x759654c77c
	private AnimationData <>xLuaBaseProxy_GetAnimationData(String P0, Boolean P1) { }
	// RVA: 0x3f34788 VA: 0x759654c788
	private Single <>xLuaBaseProxy_PlayAnimationInternal(String P0, Boolean P1, Single P2) { }
	// RVA: 0x3f34794 VA: 0x759654c794
	private Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32 P0) { }
}
```