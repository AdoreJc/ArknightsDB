# FxUVRotation

**Namespace:** `Torappu.Fx`


## Fields

- `String _propertyName`

- `Boolean _rotateTex1`

- `Single angle1`

- `Boolean _rotateTex2`

- `Single _angle2`

- `Boolean _rotateTex3`

- `Single _angle3`

- `Boolean _rotateTex4`

- `Single _angle4`

- `Material m_activeMaterial`

- `Renderer m_renderer`

- `Int32 m_rotationPropertyID0`

- `Int32 m_rotationPropertyID1`

- `Int32 m_rotationPropertyID2`

- `Int32 m_rotationPropertyID3`


## Properties

- `Material activeMaterial`

- `Boolean rotateTex1`

- `Boolean rotateTex2`

- `Boolean rotateTex3`

- `Boolean rotateTex4`


## Methods

- `Material get_activeMaterial()`

- `Boolean get_rotateTex1()`

- `Boolean get_rotateTex2()`

- `Boolean get_rotateTex3()`

- `Boolean get_rotateTex4()`

- `Void Awake()`

- `Void Update()`

- `Void _Initialize()`

- `Vector4 _CalculateMatrix(Single)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Fx
public class FxUVRotation : MonoBehaviour, IHotfixable
{
	private const String HG_UV_ROTATION_KEYWORD; // 0x0
	private static readonly Vector4 IDENTITY; // 0x0
	private String _propertyName; // 0x18
	private Boolean _rotateTex1; // 0x20
	private Single angle1; // 0x24
	private Boolean _rotateTex2; // 0x28
	private Single _angle2; // 0x2c
	private Boolean _rotateTex3; // 0x30
	private Single _angle3; // 0x34
	private Boolean _rotateTex4; // 0x38
	private Single _angle4; // 0x3c
	private Material m_activeMaterial; // 0x40
	private Renderer m_renderer; // 0x48
	private Int32 m_rotationPropertyID0; // 0x50
	private Int32 m_rotationPropertyID1; // 0x54
	private Int32 m_rotationPropertyID2; // 0x58
	private Int32 m_rotationPropertyID3; // 0x5c
	private static DelegateBridge __Hotfix0_get_activeMaterial; // 0x10
	private static DelegateBridge __Hotfix0_get_rotateTex1; // 0x18
	private static DelegateBridge __Hotfix0_get_rotateTex2; // 0x20
	private static DelegateBridge __Hotfix0_get_rotateTex3; // 0x28
	private static DelegateBridge __Hotfix0_get_rotateTex4; // 0x30
	private static DelegateBridge __Hotfix0_Awake; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge __Hotfix0__Initialize; // 0x48
	private static DelegateBridge __Hotfix0__CalculateMatrix; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Material activeMaterial { get; }
	private Boolean rotateTex1 { get; }
	private Boolean rotateTex2 { get; }
	private Boolean rotateTex3 { get; }
	private Boolean rotateTex4 { get; }

	// RVA: 0x3eff254 VA: 0x7596517254
	private Material get_activeMaterial() { }
	// RVA: 0x3eff340 VA: 0x7596517340
	private Boolean get_rotateTex1() { }
	// RVA: 0x3eff3b8 VA: 0x75965173b8
	private Boolean get_rotateTex2() { }
	// RVA: 0x3eff430 VA: 0x7596517430
	private Boolean get_rotateTex3() { }
	// RVA: 0x3eff4a8 VA: 0x75965174a8
	private Boolean get_rotateTex4() { }
	// RVA: 0x3eff520 VA: 0x7596517520
	private Void Awake() { }
	// RVA: 0x3eff81c VA: 0x759651781c
	private Void Update() { }
	// RVA: 0x3eff5e4 VA: 0x75965175e4
	private Void _Initialize() { }
	// RVA: 0x3effa0c VA: 0x7596517a0c
	private Vector4 _CalculateMatrix(Single angle) { }
	// RVA: 0x3effab0 VA: 0x7596517ab0
	private Void OnDestroy() { }
	// RVA: 0x3effb7c VA: 0x7596517b7c
	public Void .ctor() { }
	// RVA: 0x3effc2c VA: 0x7596517c2c
	private static Void .cctor() { }
}
```