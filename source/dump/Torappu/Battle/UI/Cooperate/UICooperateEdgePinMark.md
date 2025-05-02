# UICooperateEdgePinMark

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `RectTransform _mark`

- `RectTransform _markIconPos`

- `Single _cameraMoveDuration`

- `Single m_speed`

- `Int32 m_curType`

- `Transform <target>k__BackingField`

- `Vector2 <screenPos>k__BackingField`


## Properties

- `Transform target`

- `Vector2 screenPos`

- `Boolean hasTarget`


## Methods

- `Transform get_target()`

- `Void set_target(Transform)`

- `Vector2 get_screenPos()`

- `Void set_screenPos(Vector2)`

- `Void ResetMark()`

- `Void MarkUpdate(Vector3, Single)`

- `Void SetTarget(Transform, Single, Int32)`

- `Void ClearTarget()`

- `Boolean SetActiveInternal(Boolean)`

- `Void OnCameraMove()`

- `Boolean get_hasTarget()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateEdgePinMark : MonoBehaviour, IHotfixable
{
	private RectTransform _mark; // 0x18
	private RectTransform _markIconPos; // 0x20
	private List`1 _icons; // 0x28
	private Single _cameraMoveDuration; // 0x30
	private Single m_speed; // 0x34
	private Int32 m_curType; // 0x38
	private Transform <target>k__BackingField; // 0x40
	private Vector2 <screenPos>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_target; // 0x0
	private static DelegateBridge __Hotfix0_set_target; // 0x8
	private static DelegateBridge __Hotfix0_get_screenPos; // 0x10
	private static DelegateBridge __Hotfix0_set_screenPos; // 0x18
	private static DelegateBridge __Hotfix0_ResetMark; // 0x20
	private static DelegateBridge __Hotfix0_MarkUpdate; // 0x28
	private static DelegateBridge __Hotfix0_SetTarget; // 0x30
	private static DelegateBridge __Hotfix0_ClearTarget; // 0x38
	private static DelegateBridge __Hotfix0_SetActiveInternal; // 0x40
	private static DelegateBridge __Hotfix0_OnCameraMove; // 0x48
	private static DelegateBridge __Hotfix0_get_hasTarget; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public Transform target { get; set; }
	public Vector2 screenPos { get; set; }
	public Boolean hasTarget { get; }

	// RVA: 0x20e87a8 VA: 0x75947007a8
	public Transform get_target() { }
	// RVA: 0x20e8810 VA: 0x7594700810
	private Void set_target(Transform value) { }
	// RVA: 0x20e8894 VA: 0x7594700894
	public Vector2 get_screenPos() { }
	// RVA: 0x20e88f8 VA: 0x75947008f8
	public Void set_screenPos(Vector2 value) { }
	// RVA: 0x20e897c VA: 0x759470097c
	public Void ResetMark() { }
	// RVA: 0x20e8c4c VA: 0x7594700c4c
	public Void MarkUpdate(Vector3 pos, Single angle) { }
	// RVA: 0x20e8f90 VA: 0x7594700f90
	public Void SetTarget(Transform tile, Single speed, Int32 type) { }
	// RVA: 0x20e9088 VA: 0x7594701088
	public Void ClearTarget() { }
	// RVA: 0x20e89f4 VA: 0x75947009f4
	public Boolean SetActiveInternal(Boolean active) { }
	// RVA: 0x20e9110 VA: 0x7594701110
	public Void OnCameraMove() { }
	// RVA: 0x20e9268 VA: 0x7594701268
	public Boolean get_hasTarget() { }
	// RVA: 0x20e934c VA: 0x759470134c
	public Void .ctor() { }
}
```