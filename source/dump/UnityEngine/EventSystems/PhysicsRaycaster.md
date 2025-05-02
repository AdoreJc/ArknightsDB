# PhysicsRaycaster

**Namespace:** `UnityEngine.EventSystems`


## Fields

- `Camera m_EventCamera`

- `LayerMask m_EventMask`

- `Int32 m_MaxRayIntersections`

- `Int32 m_LastMaxRayIntersections`


## Properties

- `Int32 finalEventMask`

- `LayerMask eventMask`

- `Int32 maxRayIntersections`


## Methods

- `Int32 get_finalEventMask()`

- `LayerMask get_eventMask()`

- `Void set_eventMask(LayerMask)`

- `Int32 get_maxRayIntersections()`

- `Void set_maxRayIntersections(Int32)`

- `Boolean ComputeRayAndDistance(PointerEventData, ref, ref, ref)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.EventSystems
public class PhysicsRaycaster : BaseRaycaster
{
	protected const Int32 kNoEventMaskSet; // 0x0
	protected Camera m_EventCamera; // 0x20
	protected LayerMask m_EventMask; // 0x28
	protected Int32 m_MaxRayIntersections; // 0x2c
	protected Int32 m_LastMaxRayIntersections; // 0x30
	private RaycastHit[] m_Hits; // 0x38

	public override Camera eventCamera { get; }
	public virtual Int32 depth { get; }
	public Int32 finalEventMask { get; }
	public LayerMask eventMask { get; set; }
	public Int32 maxRayIntersections { get; set; }

	// RVA: 0x6a80f30 VA: 0x7599098f30
	protected Void .ctor() { }
	// RVA: 0x6a81b38 VA: 0x7599099b38
	public override Camera get_eventCamera() { }
	// RVA: 0x6a81bf4 VA: 0x7599099bf4
	public virtual Int32 get_depth() { }
	// RVA: 0x6a81a74 VA: 0x7599099a74
	public Int32 get_finalEventMask() { }
	// RVA: 0x6a81cb8 VA: 0x7599099cb8
	public LayerMask get_eventMask() { }
	// RVA: 0x6a81cc0 VA: 0x7599099cc0
	public Void set_eventMask(LayerMask value) { }
	// RVA: 0x6a81cc8 VA: 0x7599099cc8
	public Int32 get_maxRayIntersections() { }
	// RVA: 0x6a81cd0 VA: 0x7599099cd0
	public Void set_maxRayIntersections(Int32 value) { }
	// RVA: 0x6a81774 VA: 0x7599099774
	protected Boolean ComputeRayAndDistance(PointerEventData eventData, ref Ray ray, ref Int32 eventDisplayIndex, ref Single distanceToClipPlane) { }
	// RVA: 0x6a81cd8 VA: 0x7599099cd8
	public override Void Raycast(PointerEventData eventData, List`1 resultAppendList) { }
}
```