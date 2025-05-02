# PanelTemplate

**Namespace:** `Torappu.Battle.DevelopTools`


## Fields

- `KeyCode switchKeyCode`

- `KeyCode turnPageKeyCode`

- `Color highlight`

- `RectTransform _panels`

- `GameObject _battleInfoPanel`

- `RectTransform _panelShow`

- `Transform _pages`

- `Image _lastPage`

- `Single m_turnTime`

- `Int32 m_currentPage`

- `Tween m_tween`

- `Single m_scaleSpeed`

- `Vector3 m_nextScale`

- `Single m_scrollWheel`

- `Boolean m_isPointEnter`

- `Vector3 m_lastPointerPos`

- `Boolean m_isPointPressed`


## Properties

- `Single oPosX`

- `Single panelWidth`

- `Int32 maxPage`


## Methods

- `Single get_oPosX()`

- `Single get_panelWidth()`

- `Int32 get_maxPage()`

- `Void Awake()`

- `Void _SwitchPage(Int32)`

- `Void _MovePanel()`

- `Void SwitchPage(Transform)`

- `Void OpenOrCloseCheatManagerUI()`

- `Void OnPointerDown(PointerEventData)`

- `Void OnPointerUp(PointerEventData)`

- `Void OnPointerEnter(PointerEventData)`

- `Void OnPointerExit(PointerEventData)`

- `Void <_MovePanel>b__26_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.DevelopTools
public class PanelTemplate : MonoBehaviour, IPointerDownHandler, IEventSystemHandler, IPointerUpHandler, IPointerEnterHandler, IPointerExitHandler
{
	protected KeyCode switchKeyCode; // 0x18
	protected KeyCode turnPageKeyCode; // 0x1c
	protected Color highlight; // 0x20
	private RectTransform _panels; // 0x30
	private GameObject _battleInfoPanel; // 0x38
	private RectTransform _panelShow; // 0x40
	private Transform _pages; // 0x48
	private Image _lastPage; // 0x50
	private Single m_turnTime; // 0x58
	private Int32 m_currentPage; // 0x5c
	private Tween m_tween; // 0x60
	private Single m_scaleSpeed; // 0x68
	private Vector3 m_nextScale; // 0x6c
	private Single m_scrollWheel; // 0x78
	private Boolean m_isPointEnter; // 0x7c
	private Vector3 m_lastPointerPos; // 0x80
	private Boolean m_isPointPressed; // 0x8c

	private Single oPosX { get; }
	private Single panelWidth { get; }
	private Int32 maxPage { get; }

	// RVA: 0x1d2c9d4 VA: 0x75943449d4
	private Single get_oPosX() { }
	// RVA: 0x1d2c9ec VA: 0x75943449ec
	private Single get_panelWidth() { }
	// RVA: 0x1d2ca2c VA: 0x7594344a2c
	private Int32 get_maxPage() { }
	// RVA: 0x1d2ca48 VA: 0x7594344a48
	private Void Awake() { }
	// RVA: 0x1d2ca78 VA: 0x7594344a78
	public virtual Void OnUpdate() { }
	// RVA: 0x1d2cd2c VA: 0x7594344d2c
	private Void _SwitchPage(Int32 nextPage) { }
	// RVA: 0x1d2ce1c VA: 0x7594344e1c
	private Void _MovePanel() { }
	// RVA: 0x1d2cf54 VA: 0x7594344f54
	public Void SwitchPage(Transform page) { }
	// RVA: 0x1d2cc50 VA: 0x7594344c50
	public Void OpenOrCloseCheatManagerUI() { }
	// RVA: 0x1d2cf88 VA: 0x7594344f88
	public Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x1d2cfc0 VA: 0x7594344fc0
	public Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x1d2d02c VA: 0x759434502c
	public Void OnPointerEnter(PointerEventData eventData) { }
	// RVA: 0x1d2d038 VA: 0x7594345038
	public Void OnPointerExit(PointerEventData eventData) { }
	// RVA: 0x1d2c690 VA: 0x7594344690
	public Void .ctor() { }
	// RVA: 0x1d2d040 VA: 0x7594345040
	private Void <_MovePanel>b__26_0() { }
}
```