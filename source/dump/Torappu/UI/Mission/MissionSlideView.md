# MissionSlideView

**Namespace:** `Torappu.UI.Mission`


## Fields

- `Image _clippingPlane`

- `GameObject _backPart`

- `RectTransform _bookPanel`

- `RectTransform _dragPart`

- `RectTransform _finishPart`

- `Transform maskContainer`

- `UnityEvent OnFlip`

- `Single otherScale`

- `Vector3 ans`

- `Vector3 m_inputMouse`

- `Boolean m_isDraging`

- `Boolean m_interactable`

- `Single m_radius1`

- `Single m_radius2`

- `Vector3 m_sb`

- `Vector3 m_st`

- `Vector3 m_c`

- `Vector3 m_ebr`

- `Vector3 m_ebl`

- `Vector3 m_followPoint`


## Methods

- `Void SetMaskParent(Transform)`

- `Void OnMouseDragPage()`

- `Void CheckFlip()`

- `Void OnRelease()`

- `Void TweenBack()`

- `IEnumerator TweenTo(Vector3, Action)`

- `Void _DragRightPageToPoint(Vector3)`

- `Void _UpdatePanel(Vector3)`

- `Void Start()`

- `Void Update()`

- `Vector3 _TransformPoint(Vector3)`

- `Vector3 _TransformScreenPoint(Vector3)`

- `Vector3 _CalcPosition(Vector3)`

- `Single _CalcT0T1Angle(Vector3, Vector3, out)`

- `Single _NormalizeT1X(Single, Vector3, Vector3)`

- `Void <TweenBack>b__19_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionSlideView : MonoBehaviour
{
	private const Single INITSCALE; // 0x0
	private const Single INITX; // 0x0
	private const Single INITY; // 0x0
	private Image _clippingPlane; // 0x18
	private GameObject _backPart; // 0x20
	private RectTransform _bookPanel; // 0x28
	private RectTransform _dragPart; // 0x30
	private RectTransform _finishPart; // 0x38
	public Transform maskContainer; // 0x40
	public UnityEvent OnFlip; // 0x48
	public Single otherScale; // 0x50
	public Vector3 ans; // 0x54
	private Vector3 m_inputMouse; // 0x60
	private Boolean m_isDraging; // 0x6c
	private Boolean m_interactable; // 0x6d
	private Single m_radius1; // 0x70
	private Single m_radius2; // 0x74
	private Vector3 m_sb; // 0x78
	private Vector3 m_st; // 0x84
	private Vector3 m_c; // 0x90
	private Vector3 m_ebr; // 0x9c
	private Vector3 m_ebl; // 0xa8
	private Vector3 m_followPoint; // 0xb4


	// RVA: 0x2731230 VA: 0x7594d49230
	public Void SetMaskParent(Transform maskContainer) { }
	// RVA: 0x2731260 VA: 0x7594d49260
	public Void OnMouseDragPage() { }
	// RVA: 0x27318d8 VA: 0x7594d498d8
	public Void CheckFlip() { }
	// RVA: 0x27319cc VA: 0x7594d499cc
	public Void OnRelease() { }
	// RVA: 0x2731a3c VA: 0x7594d49a3c
	public Void TweenBack() { }
	// RVA: 0x2731af4 VA: 0x7594d49af4
	public IEnumerator TweenTo(Vector3 to, Action onFinish) { }
	// RVA: 0x2731740 VA: 0x7594d49740
	private Void _DragRightPageToPoint(Vector3 point) { }
	// RVA: 0x2731bd0 VA: 0x7594d49bd0
	private Void _UpdatePanel(Vector3 followLocation) { }
	// RVA: 0x2731358 VA: 0x7594d49358
	private Void Start() { }
	// RVA: 0x2732300 VA: 0x7594d4a300
	private Void Update() { }
	// RVA: 0x27321f4 VA: 0x7594d4a1f4
	private Vector3 _TransformPoint(Vector3 global) { }
	// RVA: 0x2731600 VA: 0x7594d49600
	public Vector3 _TransformScreenPoint(Vector3 global) { }
	// RVA: 0x2731f98 VA: 0x7594d49f98
	private Vector3 _CalcPosition(Vector3 followLocation) { }
	// RVA: 0x2732154 VA: 0x7594d4a154
	private Single _CalcT0T1Angle(Vector3 c, Vector3 bookCorner, out Vector3 t1) { }
	// RVA: 0x27323c8 VA: 0x7594d4a3c8
	private Single _NormalizeT1X(Single t1, Vector3 corner, Vector3 sb) { }
	// RVA: 0x27323f0 VA: 0x7594d4a3f0
	public Void .ctor() { }
	// RVA: 0x27324ac VA: 0x7594d4a4ac
	private Void <TweenBack>b__19_0() { }
}
```