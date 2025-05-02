# ThreeFaceAnimator

**Namespace:** `Torappu.Battle`


## Fields

- `FaceConfiguration _down`


## Properties

- `FaceConfiguration down`


## Methods

- `FaceConfiguration get_down()`

- `Color <>xLuaBaseProxy_get_color()`

- `Void <>xLuaBaseProxy_set_color(Color)`

- `Boolean <>xLuaBaseProxy_get_faceToDown()`

- `Void <>xLuaBaseProxy_Init(Unit)`

- `Void <>xLuaBaseProxy_OnReset(UnitAnimator)`

- `Void <>xLuaBaseProxy__SetFourDirection(Direction, Direction)`

- `Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32)`

- `Void <>xLuaBaseProxy_ForEachSkeleton(Action`1)`

- `Boolean <>xLuaBaseProxy_TryGetSpinePrefix(out)`

- `Void <>xLuaBaseProxy_SetBaseline(FP)`

- `Void <>xLuaBaseProxy_ReplaceShader()`

- `Void <>xLuaBaseProxy_SetSpineSkinInternal(SpineSkinData)`

- `Void <>xLuaBaseProxy_UpdateSpineSkinData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ThreeFaceAnimator : CharacterAnimator
{
	private FaceConfiguration _down; // 0x118
	private static DelegateBridge __Hotfix0_get_down; // 0x0
	private static DelegateBridge __Hotfix0_get_color; // 0x8
	private static DelegateBridge __Hotfix0_set_color; // 0x10
	private static DelegateBridge __Hotfix0_get_faceToDown; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_OnReset; // 0x28
	private static DelegateBridge __Hotfix0__SetFourDirection; // 0x30
	private static DelegateBridge __Hotfix0_DoUpdateFaceSign; // 0x38
	private static DelegateBridge __Hotfix0_ForEachSkeleton; // 0x40
	private static DelegateBridge __Hotfix0_TryGetSpinePrefix; // 0x48
	private static DelegateBridge __Hotfix0_SetBaseline; // 0x50
	private static DelegateBridge __Hotfix0_ReplaceShader; // 0x58
	private static DelegateBridge __Hotfix0_SetSpineSkinInternal; // 0x60
	private static DelegateBridge __Hotfix0_UpdateSpineSkinData; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public FaceConfiguration down { get; }
	public override Color color { get; set; }
	public override Boolean faceToDown { get; }

	// RVA: 0x3f5df24 VA: 0x7596575f24
	public FaceConfiguration get_down() { }
	// RVA: 0x3f5df8c VA: 0x7596575f8c
	public override Color get_color() { }
	// RVA: 0x3f5dffc VA: 0x7596575ffc
	public override Void set_color(Color value) { }
	// RVA: 0x3f5e110 VA: 0x7596576110
	public override Boolean get_faceToDown() { }
	// RVA: 0x3f5e18c VA: 0x759657618c
	public override Void Init(Unit host) { }
	// RVA: 0x3f5e2d8 VA: 0x75965762d8
	public override Void OnReset(UnitAnimator old) { }
	// RVA: 0x3f5e3d4 VA: 0x75965763d4
	protected override Void _SetFourDirection(Direction lOrR, Direction uOrD) { }
	// RVA: 0x3f5e568 VA: 0x7596576568
	protected override Void DoUpdateFaceSign(Int32 faceSign) { }
	// RVA: 0x3f5e608 VA: 0x7596576608
	protected override Void ForEachSkeleton(Action`1 func) { }
	// RVA: 0x3f5e6c0 VA: 0x75965766c0
	protected override Boolean TryGetSpinePrefix(out String prefix) { }
	// RVA: 0x3f5e860 VA: 0x7596576860
	public override Void SetBaseline(FP height) { }
	// RVA: 0x3f5e9f0 VA: 0x75965769f0
	public override Void ReplaceShader() { }
	// RVA: 0x3f5eaf4 VA: 0x7596576af4
	protected override Void SetSpineSkinInternal(SpineSkinData data) { }
	// RVA: 0x3f5eda0 VA: 0x7596576da0
	protected override Void UpdateSpineSkinData() { }
	// RVA: 0x3f5f13c VA: 0x759657713c
	public Void .ctor() { }
	// RVA: 0x3f5f1ac VA: 0x75965771ac
	private Color <>xLuaBaseProxy_get_color() { }
	// RVA: 0x3f5f1b4 VA: 0x75965771b4
	private Void <>xLuaBaseProxy_set_color(Color P0) { }
	// RVA: 0x3f5f1bc VA: 0x75965771bc
	private Boolean <>xLuaBaseProxy_get_faceToDown() { }
	// RVA: 0x3f5f224 VA: 0x7596577224
	private Void <>xLuaBaseProxy_Init(Unit P0) { }
	// RVA: 0x3f5f22c VA: 0x759657722c
	private Void <>xLuaBaseProxy_OnReset(UnitAnimator P0) { }
	// RVA: 0x3f5f234 VA: 0x7596577234
	private Void <>xLuaBaseProxy__SetFourDirection(Direction P0, Direction P1) { }
	// RVA: 0x3f5f23c VA: 0x759657723c
	private Void <>xLuaBaseProxy_DoUpdateFaceSign(Int32 P0) { }
	// RVA: 0x3f5f244 VA: 0x7596577244
	private Void <>xLuaBaseProxy_ForEachSkeleton(Action`1 P0) { }
	// RVA: 0x3f5f24c VA: 0x759657724c
	private Boolean <>xLuaBaseProxy_TryGetSpinePrefix(out String P0) { }
	// RVA: 0x3f5f254 VA: 0x7596577254
	private Void <>xLuaBaseProxy_SetBaseline(FP P0) { }
	// RVA: 0x3f5f25c VA: 0x759657725c
	private Void <>xLuaBaseProxy_ReplaceShader() { }
	// RVA: 0x3f5f264 VA: 0x7596577264
	private Void <>xLuaBaseProxy_SetSpineSkinInternal(SpineSkinData P0) { }
	// RVA: 0x3f5f26c VA: 0x759657726c
	private Void <>xLuaBaseProxy_UpdateSpineSkinData() { }
}
```