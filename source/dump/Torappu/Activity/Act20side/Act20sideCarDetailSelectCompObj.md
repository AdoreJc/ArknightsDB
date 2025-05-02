# Act20sideCarDetailSelectCompObj

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Image _itemIcon`

- `GameObject _selectPart`

- `CanvasGroup _havePart`

- `CanvasGroup _notHavePart`

- `CartAccessoryPos _pos`

- `AccessPosEvent clickEvent`

- `Tween m_switchTween`

- `Single m_boolFlag`


## Properties

- `CartAccessoryPos pos`


## Methods

- `CartAccessoryPos get_pos()`

- `Void OnClickPos()`

- `Void ApplySelectState(CartAccessoryPos)`

- `Void Render(String)`

- `Single <Render>b__13_0()`

- `Void <Render>b__13_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideCarDetailSelectCompObj : MonoBehaviour, IHotfixable
{
	private const Single DELTA_TIME; // 0x0
	private Image _itemIcon; // 0x18
	private GameObject _selectPart; // 0x20
	private CanvasGroup _havePart; // 0x28
	private CanvasGroup _notHavePart; // 0x30
	private CartAccessoryPos _pos; // 0x38
	public AccessPosEvent clickEvent; // 0x40
	private Tween m_switchTween; // 0x48
	private Single m_boolFlag; // 0x50
	private static DelegateBridge __Hotfix0_get_pos; // 0x0
	private static DelegateBridge __Hotfix0_OnClickPos; // 0x8
	private static DelegateBridge __Hotfix0_ApplySelectState; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public CartAccessoryPos pos { get; }

	// RVA: 0x32ee144 VA: 0x7595906144
	public CartAccessoryPos get_pos() { }
	// RVA: 0x32ee1ac VA: 0x75959061ac
	public Void OnClickPos() { }
	// RVA: 0x32ee24c VA: 0x759590624c
	public Void ApplySelectState(CartAccessoryPos pos) { }
	// RVA: 0x32ee2d8 VA: 0x75959062d8
	public Void Render(String compId) { }
	// RVA: 0x32ee52c VA: 0x759590652c
	public Void .ctor() { }
	// RVA: 0x32ee59c VA: 0x759590659c
	private Single <Render>b__13_0() { }
	// RVA: 0x32ee5a4 VA: 0x75959065a4
	private Void <Render>b__13_1(Single val) { }
}
```