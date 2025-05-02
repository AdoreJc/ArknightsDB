# SingleSpineAnimator

**Namespace:** `Torappu.Battle`


## Fields

- `SkeletonAnimation _skeleton`

- `FaceSwitcher _faceSwitcher`

- `Transform _muzzleTransform`

- `Transform _hitTransform`

- `Transform _headTransform`

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

- `Renderer m_renderer`

- `MeshFilter m_meshFilter`

- `MaterialPropertyBlock m_propertyBlock`


## Properties

- `Renderer renderer`

- `MaterialPropertyBlock propertyBlock`


## Methods

- `Renderer get_renderer()`

- `MaterialPropertyBlock get_propertyBlock()`

- `Void _UpdateDirection(Direction, Direction)`

- `Int32 <>xLuaBaseProxy_get_faceSign()`

- `Renderer <>xLuaBaseProxy_get_meshRenderer()`

- `MeshFilter <>xLuaBaseProxy_get_meshFilter()`

- `Void <>xLuaBaseProxy_Init(Unit)`

- `Void <>xLuaBaseProxy_SyncFrom(UnitAnimator)`

- `Transform <>xLuaBaseProxy_GetMountPoint(MountPointType)`

- `Void <>xLuaBaseProxy_OnReset(UnitAnimator)`

- `Void <>xLuaBaseProxy_ReplaceShader()`

- `Void <>xLuaBaseProxy_SetBaseline(FP)`

- `Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SingleSpineAnimator : SpineAnimator
{
	private SkeletonAnimation _skeleton; // 0xd8
	private FaceSwitcher _faceSwitcher; // 0xe0
	private Transform _muzzleTransform; // 0xe8
	private Transform _hitTransform; // 0xf0
	private Transform _headTransform; // 0xf8
	private Transform _specialPoint0; // 0x100
	private Transform _specialPoint1; // 0x108
	private Transform _specialPoint2; // 0x110
	private Transform _specialPoint3; // 0x118
	private Transform _specialPoint4; // 0x120
	private Transform _specialPoint5; // 0x128
	private Transform _specialPoint6; // 0x130
	private Transform _specialPoint7; // 0x138
	private Transform _specialPoint8; // 0x140
	private Transform _specialPoint9; // 0x148
	private Transform _specialPoint10; // 0x150
	private Transform _specialPoint11; // 0x158
	private Transform _specialPoint12; // 0x160
	private Transform _specialPoint13; // 0x168
	private Transform _specialPoint14; // 0x170
	private Transform _specialPoint15; // 0x178
	private Renderer m_renderer; // 0x180
	private MeshFilter m_meshFilter; // 0x188
	private MaterialPropertyBlock m_propertyBlock; // 0x190
	private Action`2 m_UpdateDir; // 0x198
	private static DelegateBridge __Hotfix0_get_graphicTransform; // 0x0
	private static DelegateBridge __Hotfix0_get_muzzleTransform; // 0x8
	private static DelegateBridge __Hotfix0_get_hitTransform; // 0x10
	private static DelegateBridge __Hotfix0_get_footTransform; // 0x18
	private static DelegateBridge __Hotfix0_get_headTransform; // 0x20
	private static DelegateBridge __Hotfix0_get_shadowTransform; // 0x28
	private static DelegateBridge __Hotfix0_get_faceSign; // 0x30
	private static DelegateBridge __Hotfix0_get_skeleton; // 0x38
	private static DelegateBridge __Hotfix0_get_faceSwitcher; // 0x40
	private static DelegateBridge __Hotfix0_get_renderer; // 0x48
	private static DelegateBridge __Hotfix0_get_meshRenderer; // 0x50
	private static DelegateBridge __Hotfix0_get_meshFilter; // 0x58
	private static DelegateBridge __Hotfix0_get_propertyBlock; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x68
	private static DelegateBridge __Hotfix0_SyncFrom; // 0x70
	private static DelegateBridge __Hotfix0_GetMountPoint; // 0x78
	private static DelegateBridge __Hotfix0_OnReset; // 0x80
	private static DelegateBridge __Hotfix0_OnFaceChanged; // 0x88
	private static DelegateBridge __Hotfix0_ReplaceShader; // 0x90
	private static DelegateBridge __Hotfix0_SetBaseline; // 0x98
	private static DelegateBridge __Hotfix0_DoUpdateFaceSign; // 0xa0
	private static DelegateBridge __Hotfix0_ForEachSkeleton; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateDirection; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public override Transform graphicTransform { get; }
	protected override Transform muzzleTransform { get; }
	public override Transform hitTransform { get; }
	public override Transform footTransform { get; }
	public override Transform headTransform { get; }
	public override Transform shadowTransform { get; }
	public override Int32 faceSign { get; }
	public override SkeletonAnimation skeleton { get; }
	public override FaceSwitcher faceSwitcher { get; }
	protected Renderer renderer { get; }
	public override Renderer meshRenderer { get; }
	public override MeshFilter meshFilter { get; }
	protected MaterialPropertyBlock propertyBlock { get; }

	// RVA: 0x3f350d4 VA: 0x759654d0d4
	public override Transform get_graphicTransform() { }
	// RVA: 0x3f35140 VA: 0x759654d140
	protected override Transform get_muzzleTransform() { }
	// RVA: 0x3f35200 VA: 0x759654d200
	public override Transform get_hitTransform() { }
	// RVA: 0x3f352c0 VA: 0x759654d2c0
	public override Transform get_footTransform() { }
	// RVA: 0x3f35334 VA: 0x759654d334
	public override Transform get_headTransform() { }
	// RVA: 0x3f353f4 VA: 0x759654d3f4
	public override Transform get_shadowTransform() { }
	// RVA: 0x3f35468 VA: 0x759654d468
	public override Int32 get_faceSign() { }
	// RVA: 0x3f35534 VA: 0x759654d534
	public override SkeletonAnimation get_skeleton() { }
	// RVA: 0x3f3559c VA: 0x759654d59c
	public override FaceSwitcher get_faceSwitcher() { }
	// RVA: 0x3f35604 VA: 0x759654d604
	protected Renderer get_renderer() { }
	// RVA: 0x3f356dc VA: 0x759654d6dc
	public override Renderer get_meshRenderer() { }
	// RVA: 0x3f357b4 VA: 0x759654d7b4
	public override MeshFilter get_meshFilter() { }
	// RVA: 0x3f3588c VA: 0x759654d88c
	protected MaterialPropertyBlock get_propertyBlock() { }
	// RVA: 0x3f35940 VA: 0x759654d940
	public override Void Init(Unit host) { }
	// RVA: 0x3f35aa4 VA: 0x759654daa4
	public override Void SyncFrom(UnitAnimator fromAnimator) { }
	// RVA: 0x3f35bdc VA: 0x759654dbdc
	public override Transform GetMountPoint(MountPointType mountPointType) { }
	// RVA: 0x3f35d60 VA: 0x759654dd60
	public override Void OnReset(UnitAnimator old) { }
	// RVA: 0x3f35eb4 VA: 0x759654deb4
	public override Void OnFaceChanged(Vector2 newDir, Vector2 oldDir, Boolean force, Boolean isIdle) { }
	// RVA: 0x3f360a0 VA: 0x759654e0a0
	public override Void ReplaceShader() { }
	// RVA: 0x3f361ac VA: 0x759654e1ac
	public override Void SetBaseline(FP height) { }
	// RVA: 0x3f36308 VA: 0x759654e308
	protected override Void DoUpdateFaceSign(Int32 faceSign) { }
	// RVA: 0x3f363b4 VA: 0x759654e3b4
	protected override Void ForEachSkeleton(Action`1 func) { }
	// RVA: 0x3f36458 VA: 0x759654e458
	private Void _UpdateDirection(Direction lOrR, Direction fourDir) { }
	// RVA: 0x3f364e4 VA: 0x759654e4e4
	public Void .ctor() { }
	// RVA: 0x3f36554 VA: 0x759654e554
	private Int32 <>xLuaBaseProxy_get_faceSign() { }
	// RVA: 0x3f3655c VA: 0x759654e55c
	private Renderer <>xLuaBaseProxy_get_meshRenderer() { }
	// RVA: 0x3f36564 VA: 0x759654e564
	private MeshFilter <>xLuaBaseProxy_get_meshFilter() { }
	// RVA: 0x3f3656c VA: 0x759654e56c
	private Void <>xLuaBaseProxy_Init(Unit P0) { }
	// RVA: 0x3f36574 VA: 0x759654e574
	private Void <>xLuaBaseProxy_SyncFrom(UnitAnimator P0) { }
	// RVA: 0x3f3657c VA: 0x759654e57c
	private Transform <>xLuaBaseProxy_GetMountPoint(MountPointType P0) { }
	// RVA: 0x3f36584 VA: 0x759654e584
	private Void <>xLuaBaseProxy_OnReset(UnitAnimator P0) { }
	// RVA: 0x3f3658c VA: 0x759654e58c
	private Void <>xLuaBaseProxy_ReplaceShader() { }
	// RVA: 0x3f36594 VA: 0x759654e594
	private Void <>xLuaBaseProxy_SetBaseline(FP P0) { }
	// RVA: 0x3f3659c VA: 0x759654e59c
	private Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32 P0) { }
}
```