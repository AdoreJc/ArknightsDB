# UICooperateFortressEdgePanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `RectTransform _markTransform`

- `UICooperateEdgePinMark _markPrefab`

- `UICooperateEdgePinMark _markPrefabEnemy`

- `RectTransform _center`

- `Single _speed`

- `Vector2 m_screenPos`


## Methods

- `Void Start()`

- `Void Update()`

- `Int32 AttachMark(Transform, Int32)`

- `Void DetachMark(Int32, Boolean)`

- `Boolean _EdgeMarkUpdate(UICooperateEdgePinMark, out, out)`

- `Boolean _LineLineIntersection(out, Vector3, Vector3, Vector3, Vector3)`

- `Single _GetRotate(Vector2, Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateFortressEdgePanel : MonoBehaviour, IHotfixable
{
	private List`1 _edgePoints; // 0x18
	private RectTransform _markTransform; // 0x20
	private UICooperateEdgePinMark _markPrefab; // 0x28
	private UICooperateEdgePinMark _markPrefabEnemy; // 0x30
	private RectTransform _center; // 0x38
	private Single _speed; // 0x40
	private List`1 m_marks; // 0x48
	private List`1 m_marksEnemy; // 0x50
	private Vector2 m_screenPos; // 0x58
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_AttachMark; // 0x10
	private static DelegateBridge __Hotfix0_DetachMark; // 0x18
	private static DelegateBridge __Hotfix0__EdgeMarkUpdate; // 0x20
	private static DelegateBridge __Hotfix0__LineLineIntersection; // 0x28
	private static DelegateBridge __Hotfix0__GetRotate; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x20ce1e4 VA: 0x75946e61e4
	private Void Start() { }
	// RVA: 0x20ce370 VA: 0x75946e6370
	private Void Update() { }
	// RVA: 0x20cec98 VA: 0x75946e6c98
	public Int32 AttachMark(Transform tile, Int32 type) { }
	// RVA: 0x20cf188 VA: 0x75946e7188
	public Void DetachMark(Int32 markNum, Boolean isEnemy) { }
	// RVA: 0x20ce700 VA: 0x75946e6700
	private Boolean _EdgeMarkUpdate(UICooperateEdgePinMark mark, out Vector3 interactPos, out Single angle) { }
	// RVA: 0x20cf24c VA: 0x75946e724c
	private Boolean _LineLineIntersection(out Vector3 intersection, Vector3 linePoint1, Vector3 lineVec1, Vector3 linePoint2, Vector3 lineVec2) { }
	// RVA: 0x20cf46c VA: 0x75946e746c
	private Single _GetRotate(Vector2 start, Vector2 end) { }
	// RVA: 0x20cf678 VA: 0x75946e7678
	public Void .ctor() { }
}
```