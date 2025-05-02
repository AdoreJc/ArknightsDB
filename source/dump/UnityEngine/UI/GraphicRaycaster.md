# GraphicRaycaster

**Namespace:** `UnityEngine.UI`


## Fields

- `Boolean m_IgnoreReversedGraphics`

- `BlockingObjects m_BlockingObjects`

- `LayerMask m_BlockingMask`

- `Canvas m_Canvas`


## Properties

- `Boolean ignoreReversedGraphics`

- `BlockingObjects blockingObjects`

- `LayerMask blockingMask`

- `Canvas canvas`


## Methods

- `Boolean get_ignoreReversedGraphics()`

- `Void set_ignoreReversedGraphics(Boolean)`

- `BlockingObjects get_blockingObjects()`

- `Void set_blockingObjects(BlockingObjects)`

- `LayerMask get_blockingMask()`

- `Void set_blockingMask(LayerMask)`

- `Canvas get_canvas()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class GraphicRaycaster : BaseRaycaster
{
	protected const Int32 kNoEventMaskSet; // 0x0
	private Boolean m_IgnoreReversedGraphics; // 0x20
	private BlockingObjects m_BlockingObjects; // 0x24
	protected LayerMask m_BlockingMask; // 0x28
	private Canvas m_Canvas; // 0x30
	private List`1 m_RaycastResults; // 0x38
	private static readonly List`1 s_SortedGraphics; // 0x0

	public override Int32 sortOrderPriority { get; }
	public override Int32 renderOrderPriority { get; }
	public Boolean ignoreReversedGraphics { get; set; }
	public BlockingObjects blockingObjects { get; set; }
	public LayerMask blockingMask { get; set; }
	private Canvas canvas { get; }
	public override Camera eventCamera { get; }

	// RVA: 0x69219c4 VA: 0x7598f399c4
	public override Int32 get_sortOrderPriority() { }
	// RVA: 0x6921ab4 VA: 0x7598f39ab4
	public override Int32 get_renderOrderPriority() { }
	// RVA: 0x6921b08 VA: 0x7598f39b08
	public Boolean get_ignoreReversedGraphics() { }
	// RVA: 0x6921b10 VA: 0x7598f39b10
	public Void set_ignoreReversedGraphics(Boolean value) { }
	// RVA: 0x6921b1c VA: 0x7598f39b1c
	public BlockingObjects get_blockingObjects() { }
	// RVA: 0x6921b24 VA: 0x7598f39b24
	public Void set_blockingObjects(BlockingObjects value) { }
	// RVA: 0x6921b2c VA: 0x7598f39b2c
	public LayerMask get_blockingMask() { }
	// RVA: 0x6921b34 VA: 0x7598f39b34
	public Void set_blockingMask(LayerMask value) { }
	// RVA: 0x6921b3c VA: 0x7598f39b3c
	protected Void .ctor() { }
	// RVA: 0x6921a0c VA: 0x7598f39a0c
	private Canvas get_canvas() { }
	// RVA: 0x6921bdc VA: 0x7598f39bdc
	public override Void Raycast(PointerEventData eventData, List`1 resultAppendList) { }
	// RVA: 0x6922ed0 VA: 0x7598f3aed0
	public override Camera get_eventCamera() { }
	// RVA: 0x6922948 VA: 0x7598f3a948
	private static Void Raycast(Canvas canvas, Camera eventCamera, Vector2 pointerPosition, IList`1 foundGraphics, List`1 results) { }
	// RVA: 0x6922f98 VA: 0x7598f3af98
	private static Void .cctor() { }
}
```