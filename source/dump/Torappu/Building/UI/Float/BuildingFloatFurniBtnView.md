# BuildingFloatFurniBtnView

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Button _button`

- `GameObject _highlightButtonObject`

- `AnimationWrapper _highlightBtnAnimWrapper`

- `Coroutine m_interactCoroutine`


## Methods

- `Void OnFurniBtnViewInit(RoomSlotModel)`

- `Void OnFurniBtnViewEnable(RoomSlotModel)`

- `Void OnFurniBtnViewDisable()`

- `Void OnFurniBtnViewExit()`

- `Void OnStateUpdated(RoomSlotModel)`

- `Void OnFurniBtnClick(RoomSlotModel)`

- `IEnumerator _DisableButton(VDIYRoom)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatFurniBtnView : MonoBehaviour, IHotfixable
{
	private const String HIGHLIGHT_BUTTON_ANIM_START; // 0x0
	private const String HIGHLIGHT_BUTTON_ANIM_END; // 0x0
	private const String HIGHLIGHT_BUTTON_ANIM_RESET; // 0x0
	private Button _button; // 0x18
	private GameObject _highlightButtonObject; // 0x20
	private AnimationWrapper _highlightBtnAnimWrapper; // 0x28
	private Coroutine m_interactCoroutine; // 0x30
	private static DelegateBridge __Hotfix0_OnFurniBtnViewInit; // 0x0
	private static DelegateBridge __Hotfix0_OnFurniBtnViewEnable; // 0x8
	private static DelegateBridge __Hotfix0_OnFurniBtnViewDisable; // 0x10
	private static DelegateBridge __Hotfix0_OnFurniBtnViewExit; // 0x18
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x20
	private static DelegateBridge __Hotfix0_OnFurniBtnClick; // 0x28
	private static DelegateBridge __Hotfix0__DisableButton; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3e27e68 VA: 0x759643fe68
	public Void OnFurniBtnViewInit(RoomSlotModel roomModel) { }
	// RVA: 0x3e27c18 VA: 0x759643fc18
	public Void OnFurniBtnViewEnable(RoomSlotModel roomModel) { }
	// RVA: 0x3e27ddc VA: 0x759643fddc
	public Void OnFurniBtnViewDisable() { }
	// RVA: 0x3e28458 VA: 0x7596440458
	public Void OnFurniBtnViewExit() { }
	// RVA: 0x3e28a00 VA: 0x7596440a00
	public Void OnStateUpdated(RoomSlotModel roomModel) { }
	// RVA: 0x3e28e10 VA: 0x7596440e10
	public Void OnFurniBtnClick(RoomSlotModel roomModel) { }
	// RVA: 0x3e2c518 VA: 0x7596444518
	private IEnumerator _DisableButton(VDIYRoom room) { }
	// RVA: 0x3e2c610 VA: 0x7596444610
	public Void .ctor() { }
}
```