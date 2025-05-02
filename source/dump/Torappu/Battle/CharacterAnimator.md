# CharacterAnimator

**Namespace:** `Torappu.Battle`


## Fields

- `FaceSwitcher _faceSwitcher`

- `FaceConfiguration _front`

- `FaceConfiguration _back`

- `Boolean _useNewSpineFormat`

- `Boolean m_forceFaceFront`

- `Color m_color`

- `FaceConfiguration m_activeFace`


## Properties

- `Boolean forceFaceFront`

- `FaceConfiguration front`

- `FaceConfiguration back`

- `FaceConfiguration activeFace`


## Methods

- `Boolean get_forceFaceFront()`

- `Void set_forceFaceFront(Boolean)`

- `FaceConfiguration get_front()`

- `FaceConfiguration get_back()`

- `FaceConfiguration get_activeFace()`

- `Void Init_Base_SpineAnimator(Unit)`

- `Direction _CalculateLOrRDirection(Vector2, Direction)`

- `Void _SwapConfiguration(FaceConfiguration, FaceConfiguration, Boolean, Boolean)`

- `Boolean <>xLuaBaseProxy_get_useNewSpineFormat()`

- `Renderer <>xLuaBaseProxy_get_meshRenderer()`

- `MeshFilter <>xLuaBaseProxy_get_meshFilter()`

- `Color <>xLuaBaseProxy_get_color()`

- `Void <>xLuaBaseProxy_set_color(Color)`

- `Boolean <>xLuaBaseProxy_get_faceToBack()`

- `Int32 <>xLuaBaseProxy_get_faceSign()`

- `Direction <>xLuaBaseProxy_get_faceLOrR()`

- `Void <>xLuaBaseProxy_Init(Unit)`

- `Transform <>xLuaBaseProxy_GetMountPoint(MountPointType)`

- `Void <>xLuaBaseProxy_OnReset(UnitAnimator)`

- `Single <>xLuaBaseProxy_PlayAnimationInternal(String, Boolean, Single)`

- `Void <>xLuaBaseProxy_SetSpineSkinInternal(SpineSkinData)`

- `Void <>xLuaBaseProxy_UpdateSpineSkinData()`

- `Void <>xLuaBaseProxy_ReplaceShader()`

- `Void <>xLuaBaseProxy_UpdateBaseline()`

- `Void <>xLuaBaseProxy_SetBaseline(FP)`

- `Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32)`

- `Boolean <>xLuaBaseProxy_TryGetSpinePrefix(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class CharacterAnimator : SpineAnimator
{
	private const Single TOLERANCE_L_OR_R_DIRECTION; // 0x0
	public const Single ADDON_TO_L_OR_R_DIRECTION; // 0x0
	private FaceSwitcher _faceSwitcher; // 0xd8
	private FaceConfiguration _front; // 0xe0
	private FaceConfiguration _back; // 0xe8
	private Boolean _useNewSpineFormat; // 0xf0
	private Boolean m_forceFaceFront; // 0xf1
	private Action`2 m_SetForDir; // 0xf8
	protected Color m_color; // 0x100
	private FaceConfiguration m_activeFace; // 0x110
	private static DelegateBridge __Hotfix0_get_useNewSpineFormat; // 0x0
	private static DelegateBridge __Hotfix0_get_forceFaceFront; // 0x8
	private static DelegateBridge __Hotfix0_set_forceFaceFront; // 0x10
	private static DelegateBridge __Hotfix0_get_front; // 0x18
	private static DelegateBridge __Hotfix0_get_back; // 0x20
	private static DelegateBridge __Hotfix0_get_meshRenderer; // 0x28
	private static DelegateBridge __Hotfix0_get_meshFilter; // 0x30
	private static DelegateBridge __Hotfix0_get_color; // 0x38
	private static DelegateBridge __Hotfix0_set_color; // 0x40
	private static DelegateBridge __Hotfix0_get_graphicTransform; // 0x48
	private static DelegateBridge __Hotfix0_get_muzzleTransform; // 0x50
	private static DelegateBridge __Hotfix0_get_hitTransform; // 0x58
	private static DelegateBridge __Hotfix0_get_footTransform; // 0x60
	private static DelegateBridge __Hotfix0_get_headTransform; // 0x68
	private static DelegateBridge __Hotfix0_get_shadowTransform; // 0x70
	private static DelegateBridge __Hotfix0_get_faceToBack; // 0x78
	private static DelegateBridge __Hotfix0_get_faceSign; // 0x80
	private static DelegateBridge __Hotfix0_get_faceLOrR; // 0x88
	private static DelegateBridge __Hotfix0_get_activeFace; // 0x90
	private static DelegateBridge __Hotfix0_get_skeleton; // 0x98
	private static DelegateBridge __Hotfix0_get_faceSwitcher; // 0xa0
	private static DelegateBridge __Hotfix0_Init; // 0xa8
	private static DelegateBridge __Hotfix0_Init_Base_SpineAnimator; // 0xb0
	private static DelegateBridge __Hotfix0_GetMountPoint; // 0xb8
	private static DelegateBridge __Hotfix0_OnReset; // 0xc0
	private static DelegateBridge __Hotfix0_OnFaceChanged; // 0xc8
	private static DelegateBridge __Hotfix0_PlayAnimationInternal; // 0xd0
	private static DelegateBridge __Hotfix0_SetSpineSkinInternal; // 0xd8
	private static DelegateBridge __Hotfix0_UpdateSpineSkinData; // 0xe0
	private static DelegateBridge __Hotfix0_ReplaceShader; // 0xe8
	private static DelegateBridge __Hotfix0_UpdateBaseline; // 0xf0
	private static DelegateBridge __Hotfix0_SetBaseline; // 0xf8
	private static DelegateBridge __Hotfix0_DoUpdateFaceSign; // 0x100
	private static DelegateBridge __Hotfix0_ForEachSkeleton; // 0x108
	private static DelegateBridge __Hotfix0__CalculateLOrRDirection; // 0x110
	private static DelegateBridge __Hotfix0__SetFourDirection; // 0x118
	private static DelegateBridge __Hotfix0__SwapConfiguration; // 0x120
	private static DelegateBridge __Hotfix0_TryGetSpinePrefix; // 0x128
	private static DelegateBridge _c__Hotfix0_ctor; // 0x130

	protected override Boolean useNewSpineFormat { get; }
	public Boolean forceFaceFront { get; set; }
	public FaceConfiguration front { get; }
	public FaceConfiguration back { get; }
	public override Renderer meshRenderer { get; }
	public override MeshFilter meshFilter { get; }
	public override Color color { get; set; }
	public override Transform graphicTransform { get; }
	protected override Transform muzzleTransform { get; }
	public override Transform hitTransform { get; }
	public override Transform footTransform { get; }
	public override Transform headTransform { get; }
	public override Transform shadowTransform { get; }
	public override Boolean faceToBack { get; }
	public override Int32 faceSign { get; }
	public override Direction faceLOrR { get; }
	protected FaceConfiguration activeFace { get; }
	public override SkeletonAnimation skeleton { get; }
	public override FaceSwitcher faceSwitcher { get; }

	// RVA: 0x3f2b11c VA: 0x759654311c
	protected override Boolean get_useNewSpineFormat() { }
	// RVA: 0x3f2b184 VA: 0x7596543184
	public Boolean get_forceFaceFront() { }
	// RVA: 0x3f2b1ec VA: 0x75965431ec
	public Void set_forceFaceFront(Boolean value) { }
	// RVA: 0x3f2b26c VA: 0x759654326c
	public FaceConfiguration get_front() { }
	// RVA: 0x3f2b2d4 VA: 0x75965432d4
	public FaceConfiguration get_back() { }
	// RVA: 0x3f2b33c VA: 0x759654333c
	public override Renderer get_meshRenderer() { }
	// RVA: 0x3f2b45c VA: 0x759654345c
	public override MeshFilter get_meshFilter() { }
	// RVA: 0x3f2b57c VA: 0x759654357c
	public override Color get_color() { }
	// RVA: 0x3f2b5ec VA: 0x75965435ec
	public override Void set_color(Color value) { }
	// RVA: 0x3f2b714 VA: 0x7596543714
	public override Transform get_graphicTransform() { }
	// RVA: 0x3f2b780 VA: 0x7596543780
	protected override Transform get_muzzleTransform() { }
	// RVA: 0x3f2b854 VA: 0x7596543854
	public override Transform get_hitTransform() { }
	// RVA: 0x3f2b928 VA: 0x7596543928
	public override Transform get_footTransform() { }
	// RVA: 0x3f2b9a4 VA: 0x75965439a4
	public override Transform get_headTransform() { }
	// RVA: 0x3f2ba78 VA: 0x7596543a78
	public override Transform get_shadowTransform() { }
	// RVA: 0x3f2bb4c VA: 0x7596543b4c
	public override Boolean get_faceToBack() { }
	// RVA: 0x3f2bbc0 VA: 0x7596543bc0
	public override Int32 get_faceSign() { }
	// RVA: 0x3f2bc9c VA: 0x7596543c9c
	public override Direction get_faceLOrR() { }
	// RVA: 0x3f2bd60 VA: 0x7596543d60
	protected FaceConfiguration get_activeFace() { }
	// RVA: 0x3f2bdc8 VA: 0x7596543dc8
	public override SkeletonAnimation get_skeleton() { }
	// RVA: 0x3f2be3c VA: 0x7596543e3c
	public override FaceSwitcher get_faceSwitcher() { }
	// RVA: 0x3f2bea4 VA: 0x7596543ea4
	public override Void Init(Unit host) { }
	// RVA: 0x3f2c1f0 VA: 0x75965441f0
	protected Void Init_Base_SpineAnimator(Unit host) { }
	// RVA: 0x3f2c274 VA: 0x7596544274
	public override Transform GetMountPoint(MountPointType mountPointType) { }
	// RVA: 0x3f2c47c VA: 0x759654447c
	public override Void OnReset(UnitAnimator old) { }
	// RVA: 0x3f2c690 VA: 0x7596544690
	public override Void OnFaceChanged(Vector2 newDir, Vector2 oldDir, Boolean force, Boolean isIdle) { }
	// RVA: 0x3f2caa4 VA: 0x7596544aa4
	protected override Single PlayAnimationInternal(String animKey, Boolean forceFromStart, Single speed) { }
	// RVA: 0x3f2ccbc VA: 0x7596544cbc
	protected override Void SetSpineSkinInternal(SpineSkinData data) { }
	// RVA: 0x3f2cee8 VA: 0x7596544ee8
	protected override Void UpdateSpineSkinData() { }
	// RVA: 0x3f2d204 VA: 0x7596545204
	public override Void ReplaceShader() { }
	// RVA: 0x3f2d3e8 VA: 0x75965453e8
	public override Void UpdateBaseline() { }
	// RVA: 0x3f2d4d4 VA: 0x75965454d4
	public override Void SetBaseline(FP height) { }
	// RVA: 0x3f2d704 VA: 0x7596545704
	protected override Void DoUpdateFaceSign(Int32 faceSign) { }
	// RVA: 0x3f2d7c4 VA: 0x75965457c4
	protected override Void ForEachSkeleton(Action`1 func) { }
	// RVA: 0x3f2c8b0 VA: 0x75965448b0
	private Direction _CalculateLOrRDirection(Vector2 newDir, Direction defaultLOrR) { }
	// RVA: 0x3f2d88c VA: 0x759654588c
	protected virtual Void _SetFourDirection(Direction lOrR, Direction uOrD) { }
	// RVA: 0x3f2bf80 VA: 0x7596543f80
	protected Void _SwapConfiguration(FaceConfiguration to, FaceConfiguration from, Boolean needSync, Boolean force) { }
	// RVA: 0x3f2d938 VA: 0x7596545938
	protected override Boolean TryGetSpinePrefix(out String prefix) { }
	// RVA: 0x3f2da98 VA: 0x7596545a98
	public Void .ctor() { }
	// RVA: 0x3f2db08 VA: 0x7596545b08
	private Boolean <>xLuaBaseProxy_get_useNewSpineFormat() { }
	// RVA: 0x3f2db10 VA: 0x7596545b10
	private Renderer <>xLuaBaseProxy_get_meshRenderer() { }
	// RVA: 0x3f2db18 VA: 0x7596545b18
	private MeshFilter <>xLuaBaseProxy_get_meshFilter() { }
	// RVA: 0x3f2db20 VA: 0x7596545b20
	private Color <>xLuaBaseProxy_get_color() { }
	// RVA: 0x3f2db28 VA: 0x7596545b28
	private Void <>xLuaBaseProxy_set_color(Color P0) { }
	// RVA: 0x3f2db30 VA: 0x7596545b30
	private Boolean <>xLuaBaseProxy_get_faceToBack() { }
	// RVA: 0x3f2db38 VA: 0x7596545b38
	private Int32 <>xLuaBaseProxy_get_faceSign() { }
	// RVA: 0x3f2db40 VA: 0x7596545b40
	private Direction <>xLuaBaseProxy_get_faceLOrR() { }
	// RVA: 0x3f2db48 VA: 0x7596545b48
	private Void <>xLuaBaseProxy_Init(Unit P0) { }
	// RVA: 0x3f2db50 VA: 0x7596545b50
	private Transform <>xLuaBaseProxy_GetMountPoint(MountPointType P0) { }
	// RVA: 0x3f2db58 VA: 0x7596545b58
	private Void <>xLuaBaseProxy_OnReset(UnitAnimator P0) { }
	// RVA: 0x3f2db60 VA: 0x7596545b60
	private Single <>xLuaBaseProxy_PlayAnimationInternal(String P0, Boolean P1, Single P2) { }
	// RVA: 0x3f2db6c VA: 0x7596545b6c
	private Void <>xLuaBaseProxy_SetSpineSkinInternal(SpineSkinData P0) { }
	// RVA: 0x3f2db74 VA: 0x7596545b74
	private Void <>xLuaBaseProxy_UpdateSpineSkinData() { }
	// RVA: 0x3f2db7c VA: 0x7596545b7c
	private Void <>xLuaBaseProxy_ReplaceShader() { }
	// RVA: 0x3f2db84 VA: 0x7596545b84
	private Void <>xLuaBaseProxy_UpdateBaseline() { }
	// RVA: 0x3f2db8c VA: 0x7596545b8c
	private Void <>xLuaBaseProxy_SetBaseline(FP P0) { }
	// RVA: 0x3f2db94 VA: 0x7596545b94
	private Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32 P0) { }
	// RVA: 0x3f2db9c VA: 0x7596545b9c
	private Boolean <>xLuaBaseProxy_TryGetSpinePrefix(out String P0) { }
}
```