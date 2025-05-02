# EventSystem

**Namespace:** `UnityEngine.EventSystems`


## Fields

- `BaseInputModule m_CurrentInputModule`

- `GameObject m_FirstSelected`

- `Boolean m_sendNavigationEvents`

- `Int32 m_DragThreshold`

- `GameObject m_CurrentSelected`

- `Boolean m_HasFocus`

- `Boolean m_SelectionGuard`

- `BaseEventData m_DummyData`


## Properties

- `Boolean sendNavigationEvents`

- `Int32 pixelDragThreshold`

- `BaseInputModule currentInputModule`

- `GameObject firstSelectedGameObject`

- `GameObject currentSelectedGameObject`

- `GameObject lastSelectedGameObject`

- `Boolean isFocused`

- `Boolean alreadySelecting`

- `BaseEventData baseEventDataCache`

- `Boolean isUIToolkitActiveEventSystem`

- `Boolean sendUIToolkitEvents`

- `Boolean createUIToolkitPanelGameObjectsOnStart`


## Methods

- `Boolean get_sendNavigationEvents()`

- `Void set_sendNavigationEvents(Boolean)`

- `Int32 get_pixelDragThreshold()`

- `Void set_pixelDragThreshold(Int32)`

- `BaseInputModule get_currentInputModule()`

- `GameObject get_firstSelectedGameObject()`

- `Void set_firstSelectedGameObject(GameObject)`

- `GameObject get_currentSelectedGameObject()`

- `GameObject get_lastSelectedGameObject()`

- `Boolean get_isFocused()`

- `Void UpdateModules()`

- `Boolean get_alreadySelecting()`

- `Void SetSelectedGameObject(GameObject, BaseEventData)`

- `BaseEventData get_baseEventDataCache()`

- `Void SetSelectedGameObject(GameObject)`

- `Void RaycastAll(PointerEventData, List`1)`

- `Boolean IsPointerOverGameObject()`

- `Boolean IsPointerOverGameObject(Int32)`

- `Boolean get_isUIToolkitActiveEventSystem()`

- `Boolean get_sendUIToolkitEvents()`

- `Boolean get_createUIToolkitPanelGameObjectsOnStart()`

- `Void CreateUIToolkitPanelGameObject(BaseRuntimePanel)`

- `Void TickModules()`

- `Void ChangeEventModule(BaseInputModule)`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.EventSystems
public class EventSystem : UIBehaviour
{
	private List`1 m_SystemInputModules; // 0x18
	private BaseInputModule m_CurrentInputModule; // 0x20
	private static List`1 m_EventSystems; // 0x0
	private GameObject m_FirstSelected; // 0x28
	private Boolean m_sendNavigationEvents; // 0x30
	private Int32 m_DragThreshold; // 0x34
	private GameObject m_CurrentSelected; // 0x38
	private Boolean m_HasFocus; // 0x40
	private Boolean m_SelectionGuard; // 0x41
	private BaseEventData m_DummyData; // 0x48
	private static readonly Comparison`1 s_RaycastComparer; // 0x8
	private static UIToolkitOverrideConfig s_UIToolkitOverride; // 0x10

	public static EventSystem current { get; set; }
	public Boolean sendNavigationEvents { get; set; }
	public Int32 pixelDragThreshold { get; set; }
	public BaseInputModule currentInputModule { get; }
	public GameObject firstSelectedGameObject { get; set; }
	public GameObject currentSelectedGameObject { get; }
	public GameObject lastSelectedGameObject { get; }
	public Boolean isFocused { get; }
	public Boolean alreadySelecting { get; }
	private BaseEventData baseEventDataCache { get; }
	private Boolean isUIToolkitActiveEventSystem { get; }
	private Boolean sendUIToolkitEvents { get; }
	private Boolean createUIToolkitPanelGameObjectsOnStart { get; }

	// RVA: 0x6a76d78 VA: 0x759908ed78
	public static EventSystem get_current() { }
	// RVA: 0x6a76e3c VA: 0x759908ee3c
	public static Void set_current(EventSystem value) { }
	// RVA: 0x6a76fd0 VA: 0x759908efd0
	public Boolean get_sendNavigationEvents() { }
	// RVA: 0x6a76fd8 VA: 0x759908efd8
	public Void set_sendNavigationEvents(Boolean value) { }
	// RVA: 0x6a76fe4 VA: 0x759908efe4
	public Int32 get_pixelDragThreshold() { }
	// RVA: 0x6a76fec VA: 0x759908efec
	public Void set_pixelDragThreshold(Int32 value) { }
	// RVA: 0x6a76ff4 VA: 0x759908eff4
	public BaseInputModule get_currentInputModule() { }
	// RVA: 0x6a76ffc VA: 0x759908effc
	public GameObject get_firstSelectedGameObject() { }
	// RVA: 0x6a77004 VA: 0x759908f004
	public Void set_firstSelectedGameObject(GameObject value) { }
	// RVA: 0x6a7700c VA: 0x759908f00c
	public GameObject get_currentSelectedGameObject() { }
	// RVA: 0x6a77014 VA: 0x759908f014
	public GameObject get_lastSelectedGameObject() { }
	// RVA: 0x6a7701c VA: 0x759908f01c
	public Boolean get_isFocused() { }
	// RVA: 0x6a77024 VA: 0x759908f024
	protected Void .ctor() { }
	// RVA: 0x6a770c0 VA: 0x759908f0c0
	public Void UpdateModules() { }
	// RVA: 0x6a77200 VA: 0x759908f200
	public Boolean get_alreadySelecting() { }
	// RVA: 0x6a75694 VA: 0x759908d694
	public Void SetSelectedGameObject(GameObject selected, BaseEventData pointer) { }
	// RVA: 0x6a77208 VA: 0x759908f208
	private BaseEventData get_baseEventDataCache() { }
	// RVA: 0x6a72ae0 VA: 0x759908aae0
	public Void SetSelectedGameObject(GameObject selected) { }
	// RVA: 0x6a77294 VA: 0x759908f294
	private static Int32 RaycastComparer(RaycastResult lhs, RaycastResult rhs) { }
	// RVA: 0x6a77718 VA: 0x759908f718
	public Void RaycastAll(PointerEventData eventData, List`1 raycastResults) { }
	// RVA: 0x6a77908 VA: 0x759908f908
	public Boolean IsPointerOverGameObject() { }
	// RVA: 0x6a77910 VA: 0x759908f910
	public Boolean IsPointerOverGameObject(Int32 pointerId) { }
	// RVA: 0x6a779b4 VA: 0x759908f9b4
	private Boolean get_isUIToolkitActiveEventSystem() { }
	// RVA: 0x6a77aa4 VA: 0x759908faa4
	private Boolean get_sendUIToolkitEvents() { }
	// RVA: 0x6a77b18 VA: 0x759908fb18
	private Boolean get_createUIToolkitPanelGameObjectsOnStart() { }
	// RVA: 0x6a77b8c VA: 0x759908fb8c
	public static Void SetUITookitEventSystemOverride(EventSystem activeEventSystem, Boolean sendEvents, Boolean createPanelGameObjectsOnStart) { }
	// RVA: 0x6a77d38 VA: 0x759908fd38
	private Void CreateUIToolkitPanelGameObject(BaseRuntimePanel panel) { }
	// RVA: 0x6a78008 VA: 0x7599090008
	protected override Void Start() { }
	// RVA: 0x6a78248 VA: 0x7599090248
	protected override Void OnDestroy() { }
	// RVA: 0x6a782f0 VA: 0x75990902f0
	protected override Void OnEnable() { }
	// RVA: 0x6a7840c VA: 0x759909040c
	protected override Void OnDisable() { }
	// RVA: 0x6a7852c VA: 0x759909052c
	private Void TickModules() { }
	// RVA: 0x6a7862c VA: 0x759909062c
	protected virtual Void OnApplicationFocus(Boolean hasFocus) { }
	// RVA: 0x6a78640 VA: 0x7599090640
	protected virtual Void Update() { }
	// RVA: 0x6a788a0 VA: 0x75990908a0
	private Void ChangeEventModule(BaseInputModule module) { }
	// RVA: 0x6a789b0 VA: 0x75990909b0
	public override String ToString() { }
	// RVA: 0x6a78b08 VA: 0x7599090b08
	private static Void .cctor() { }
}
```