# HomeIllustEditFrame

**Namespace:** `Torappu.UI.Home`


## Fields

- `RectTransform m_rectTrans`

- `Camera m_localCamera`

- `Boolean m_isDragging`

- `IDragEvent m_dragEvent`

- `IClickEvent m_clickEvent`


## Properties

- `RectTransform rectTrans`


## Methods

- `RectTransform get_rectTrans()`

- `Camera _GetLocalCamera()`

- `Void BindDragEvent(IDragEvent)`

- `Void BindClickEvent(IClickEvent)`

- `Void SyncIllustInfo(IllustHandler)`

- `Void OnDrag(PointerEventData)`

- `Void OnBeginDrag(PointerEventData)`

- `Void OnEndDrag(PointerEventData)`

- `Void OnPointerClick(PointerEventData)`

- `Void _TryBeginDrag(PointerEventData)`

- `Void _TryClick(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeIllustEditFrame : MonoBehaviour, IHotfixable, IPointerClickHandler, IEventSystemHandler, IDragHandler, IBeginDragHandler, IEndDragHandler
{
	private RectTransform m_rectTrans; // 0x18
	private Camera m_localCamera; // 0x20
	private Boolean m_isDragging; // 0x28
	private IDragEvent m_dragEvent; // 0x30
	private IClickEvent m_clickEvent; // 0x38
	private static DelegateBridge __Hotfix0_get_rectTrans; // 0x0
	private static DelegateBridge __Hotfix0__GetLocalCamera; // 0x8
	private static DelegateBridge __Hotfix0_BindDragEvent; // 0x10
	private static DelegateBridge __Hotfix0_BindClickEvent; // 0x18
	private static DelegateBridge __Hotfix0_SyncIllustInfo; // 0x20
	private static DelegateBridge __Hotfix0_OnDrag; // 0x28
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x30
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x38
	private static DelegateBridge __Hotfix0_OnPointerClick; // 0x40
	private static DelegateBridge __Hotfix0__TryBeginDrag; // 0x48
	private static DelegateBridge __Hotfix0__TryClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	protected RectTransform rectTrans { get; }

	// RVA: 0x284195c VA: 0x7594e5995c
	protected RectTransform get_rectTrans() { }
	// RVA: 0x2841a34 VA: 0x7594e59a34
	private Camera _GetLocalCamera() { }
	// RVA: 0x2841b64 VA: 0x7594e59b64
	public Void BindDragEvent(IDragEvent dragEvent) { }
	// RVA: 0x2841be8 VA: 0x7594e59be8
	public Void BindClickEvent(IClickEvent clickEvent) { }
	// RVA: 0x2841c6c VA: 0x7594e59c6c
	public Void SyncIllustInfo(IllustHandler handler) { }
	// RVA: 0x2841fd8 VA: 0x7594e59fd8
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x2842174 VA: 0x7594e5a174
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x28421f4 VA: 0x7594e5a1f4
	public Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x2842270 VA: 0x7594e5a270
	public Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x2842058 VA: 0x7594e5a058
	private Void _TryBeginDrag(PointerEventData eventData) { }
	// RVA: 0x28422f0 VA: 0x7594e5a2f0
	private Void _TryClick(PointerEventData eventData) { }
	// RVA: 0x28423ec VA: 0x7594e5a3ec
	public Void .ctor() { }
}
```