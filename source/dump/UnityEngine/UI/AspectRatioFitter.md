# AspectRatioFitter

**Namespace:** `UnityEngine.UI`


## Fields

- `AspectMode m_AspectMode`

- `Single m_AspectRatio`

- `RectTransform m_Rect`

- `Boolean m_DelayedSetDirty`

- `Boolean m_DoesParentExist`

- `DrivenRectTransformTracker m_Tracker`


## Properties

- `AspectMode aspectMode`

- `Single aspectRatio`

- `RectTransform rectTransform`


## Methods

- `AspectMode get_aspectMode()`

- `Void set_aspectMode(AspectMode)`

- `Single get_aspectRatio()`

- `Void set_aspectRatio(Single)`

- `RectTransform get_rectTransform()`

- `Void UpdateRect()`

- `Single GetSizeDeltaToProduceSize(Single, Int32)`

- `Vector2 GetParentSize()`

- `Void SetDirty()`

- `Boolean IsComponentValidOnObject()`

- `Boolean IsAspectModeValid()`

- `Boolean DoesParentExists()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class AspectRatioFitter : UIBehaviour, ILayoutSelfController, ILayoutController
{
	private AspectMode m_AspectMode; // 0x18
	private Single m_AspectRatio; // 0x1c
	private RectTransform m_Rect; // 0x20
	private Boolean m_DelayedSetDirty; // 0x28
	private Boolean m_DoesParentExist; // 0x29
	private DrivenRectTransformTracker m_Tracker; // 0x2a

	public AspectMode aspectMode { get; set; }
	public Single aspectRatio { get; set; }
	private RectTransform rectTransform { get; }

	// RVA: 0x6a51620 VA: 0x7599069620
	public AspectMode get_aspectMode() { }
	// RVA: 0x6a51628 VA: 0x7599069628
	public Void set_aspectMode(AspectMode value) { }
	// RVA: 0x6a516a0 VA: 0x75990696a0
	public Single get_aspectRatio() { }
	// RVA: 0x6a516a8 VA: 0x75990696a8
	public Void set_aspectRatio(Single value) { }
	// RVA: 0x6a5171c VA: 0x759906971c
	private RectTransform get_rectTransform() { }
	// RVA: 0x6a517c4 VA: 0x75990697c4
	protected Void .ctor() { }
	// RVA: 0x6a517d4 VA: 0x75990697d4
	protected override Void OnEnable() { }
	// RVA: 0x6a5186c VA: 0x759906986c
	protected override Void Start() { }
	// RVA: 0x6a519b0 VA: 0x75990699b0
	protected override Void OnDisable() { }
	// RVA: 0x6a51e18 VA: 0x7599069e18
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x6a51eb0 VA: 0x7599069eb0
	protected virtual Void Update() { }
	// RVA: 0x6a51ec4 VA: 0x7599069ec4
	protected override Void OnRectTransformDimensionsChange() { }
	// RVA: 0x6a51ec8 VA: 0x7599069ec8
	private Void UpdateRect() { }
	// RVA: 0x6a522dc VA: 0x759906a2dc
	private Single GetSizeDeltaToProduceSize(Single size, Int32 axis) { }
	// RVA: 0x6a521cc VA: 0x759906a1cc
	private Vector2 GetParentSize() { }
	// RVA: 0x6a523d4 VA: 0x759906a3d4
	public virtual Void SetLayoutHorizontal() { }
	// RVA: 0x6a523d8 VA: 0x759906a3d8
	public virtual Void SetLayoutVertical() { }
	// RVA: 0x6a5169c VA: 0x759906969c
	protected Void SetDirty() { }
	// RVA: 0x6a518bc VA: 0x75990698bc
	public Boolean IsComponentValidOnObject() { }
	// RVA: 0x6a51988 VA: 0x7599069988
	public Boolean IsAspectModeValid() { }
	// RVA: 0x6a523dc VA: 0x759906a3dc
	private Boolean DoesParentExists() { }
}
```