# UIMedalDIYTokenView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Image _image`

- `HexRaycastBlocker _hexRaycaster`

- `CanvasGroup _alphaHandler`

- `Status m_status`

- `DIYMedalModel m_model`

- `IMedalDIYContext m_context`

- `RectTransform m_rectTrans`


## Properties

- `RectTransform rectTrans`

- `CanvasGroup alphaHandler`

- `Boolean enableRaycast`


## Methods

- `RectTransform get_rectTrans()`

- `CanvasGroup get_alphaHandler()`

- `Boolean get_enableRaycast()`

- `Void set_enableRaycast(Boolean)`

- `Void Init(DIYMedalModel, IMedalDIYContext)`

- `Void ClearEvents()`

- `SizeConfig _LoadSizeConfig(MedalSize)`

- `Void OnPointerDown(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void OnBeginDrag(PointerEventData)`

- `Void OnEndDrag(PointerEventData)`

- `Void _TryTriggerBeginDrag(PointerEventData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalDIYTokenView : MonoBehaviour, IHotfixable, IPointerDownHandler, IEventSystemHandler, IDragHandler, IBeginDragHandler, IEndDragHandler
{
	private Image _image; // 0x18
	private HexRaycastBlocker _hexRaycaster; // 0x20
	private CanvasGroup _alphaHandler; // 0x28
	private List`1 _sizeConfigs; // 0x30
	private Status m_status; // 0x38
	private DIYMedalModel m_model; // 0x48
	private IMedalDIYContext m_context; // 0x50
	private RectTransform m_rectTrans; // 0x58
	private static DelegateBridge __Hotfix0_get_rectTrans; // 0x0
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x8
	private static DelegateBridge __Hotfix0_get_enableRaycast; // 0x10
	private static DelegateBridge __Hotfix0_set_enableRaycast; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_ClearEvents; // 0x28
	private static DelegateBridge __Hotfix0__LoadSizeConfig; // 0x30
	private static DelegateBridge __Hotfix0_OnPointerDown; // 0x38
	private static DelegateBridge __Hotfix0_OnDrag; // 0x40
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x48
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x50
	private static DelegateBridge __Hotfix0__TryTriggerBeginDrag; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public RectTransform rectTrans { get; }
	public CanvasGroup alphaHandler { get; }
	public Boolean enableRaycast { get; set; }

	// RVA: 0x278ce50 VA: 0x7594da4e50
	public RectTransform get_rectTrans() { }
	// RVA: 0x278cf50 VA: 0x7594da4f50
	public CanvasGroup get_alphaHandler() { }
	// RVA: 0x278cfb8 VA: 0x7594da4fb8
	public Boolean get_enableRaycast() { }
	// RVA: 0x278d034 VA: 0x7594da5034
	public Void set_enableRaycast(Boolean value) { }
	// RVA: 0x278d0c8 VA: 0x7594da50c8
	public Void Init(DIYMedalModel model, IMedalDIYContext context) { }
	// RVA: 0x278d484 VA: 0x7594da5484
	public Void ClearEvents() { }
	// RVA: 0x278d2d4 VA: 0x7594da52d4
	private SizeConfig _LoadSizeConfig(MedalSize size) { }
	// RVA: 0x278d51c VA: 0x7594da551c
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x278d6ac VA: 0x7594da56ac
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x278d898 VA: 0x7594da5898
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x278d918 VA: 0x7594da5918
	public Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x278d72c VA: 0x7594da572c
	private Void _TryTriggerBeginDrag(PointerEventData eventData) { }
	// RVA: 0x278da90 VA: 0x7594da5a90
	public Void .ctor() { }
}
```