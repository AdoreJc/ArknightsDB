# RectMask2D

**Namespace:** `UnityEngine.UI`


## Fields

- `RectTransform m_RectTransform`

- `Boolean m_ShouldRecalculateClipRects`

- `Rect m_LastClipRectCanvasSpace`

- `Boolean m_ForceClip`

- `Vector4 m_Padding`

- `Vector2Int m_Softness`

- `Canvas m_Canvas`


## Properties

- `Vector4 padding`

- `Vector2Int softness`

- `Rect canvasRect`

- `RectTransform rectTransform`

- `Rect rootCanvasRect`


## Methods

- `Vector4 get_padding()`

- `Void set_padding(Vector4)`

- `Vector2Int get_softness()`

- `Void set_softness(Vector2Int)`

- `Rect get_canvasRect()`

- `RectTransform get_rectTransform()`

- `Rect get_rootCanvasRect()`

- `Void AddClippable(IClippable)`

- `Void RemoveClippable(IClippable)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class RectMask2D : UIBehaviour, IClipper, ICanvasRaycastFilter
{
	private readonly RectangularVertexClipper m_VertexClipper; // 0x18
	private RectTransform m_RectTransform; // 0x20
	private HashSet`1 m_MaskableTargets; // 0x28
	private HashSet`1 m_ClipTargets; // 0x30
	private Boolean m_ShouldRecalculateClipRects; // 0x38
	private List`1 m_Clippers; // 0x40
	private Rect m_LastClipRectCanvasSpace; // 0x48
	private Boolean m_ForceClip; // 0x58
	private Vector4 m_Padding; // 0x5c
	private Vector2Int m_Softness; // 0x6c
	private Canvas m_Canvas; // 0x78
	private Vector3[] m_Corners; // 0x80

	public Vector4 padding { get; set; }
	public Vector2Int softness { get; set; }
	internal Canvas Canvas { get; }
	public Rect canvasRect { get; }
	public RectTransform rectTransform { get; }
	private Rect rootCanvasRect { get; }

	// RVA: 0x6a5df08 VA: 0x7599075f08
	public Vector4 get_padding() { }
	// RVA: 0x6a5df14 VA: 0x7599075f14
	public Void set_padding(Vector4 value) { }
	// RVA: 0x6a5df24 VA: 0x7599075f24
	public Vector2Int get_softness() { }
	// RVA: 0x6a5df2c VA: 0x7599075f2c
	public Void set_softness(Vector2Int value) { }
	// RVA: 0x6a5df48 VA: 0x7599075f48
	internal Canvas get_Canvas() { }
	// RVA: 0x6a5e0c8 VA: 0x75990760c8
	public Rect get_canvasRect() { }
	// RVA: 0x6a5e10c VA: 0x759907610c
	public RectTransform get_rectTransform() { }
	// RVA: 0x6a5e17c VA: 0x759907617c
	protected Void .ctor() { }
	// RVA: 0x6a5e310 VA: 0x7599076310
	protected override Void OnEnable() { }
	// RVA: 0x6a5e344 VA: 0x7599076344
	protected override Void OnDisable() { }
	// RVA: 0x6a5e414 VA: 0x7599076414
	protected override Void OnDestroy() { }
	// RVA: 0x6a5e434 VA: 0x7599076434
	public virtual Boolean IsRaycastLocationValid(Vector2 sp, Camera eventCamera) { }
	// RVA: 0x6a5e510 VA: 0x7599076510
	private Rect get_rootCanvasRect() { }
	// RVA: 0x6a5e62c VA: 0x759907662c
	public virtual Void PerformClipping() { }
	// RVA: 0x6a5ed50 VA: 0x7599076d50
	public virtual Void UpdateClipSoftness() { }
	// RVA: 0x6a5f044 VA: 0x7599077044
	public Void AddClippable(IClippable clippable) { }
	// RVA: 0x6a5f158 VA: 0x7599077158
	public Void RemoveClippable(IClippable clippable) { }
	// RVA: 0x6a5f2f8 VA: 0x75990772f8
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x6a5f328 VA: 0x7599077328
	protected override Void OnCanvasHierarchyChanged() { }
}
```