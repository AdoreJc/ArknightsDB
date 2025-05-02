# Act1VAutoChessCommonTopMenu

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `RectTransform _rectCommonTopMenuHolder`

- `RectTransform _returnBtnHolder`

- `RectTransform _returnBtnHotspot`

- `RectTransform _leaveBtnHolder`

- `RectTransform _leaveBtnHotspot`

- `GameObject _objInfoBtnEntryMain`

- `GameObject _objInfoBtnEntryTeam`

- `GameObject _objInfoBtnChessShopList`

- `Action <onReturnClicked>k__BackingField`

- `Action <onLeaveClicked>k__BackingField`

- `CommonTopMenu m_commonTopMenu`


## Properties

- `Action onReturnClicked`

- `Action onLeaveClicked`


## Methods

- `Action get_onReturnClicked()`

- `Void set_onReturnClicked(Action)`

- `Action get_onLeaveClicked()`

- `Void set_onLeaveClicked(Action)`

- `Void Init(InputParams)`

- `Void EventOnReturnClick()`

- `Void EventOnLeaveClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessCommonTopMenu : MonoBehaviour, IHotfixable
{
	private RectTransform _rectCommonTopMenuHolder; // 0x18
	private RectTransform _returnBtnHolder; // 0x20
	private RectTransform _returnBtnHotspot; // 0x28
	private RectTransform _leaveBtnHolder; // 0x30
	private RectTransform _leaveBtnHotspot; // 0x38
	private GameObject _objInfoBtnEntryMain; // 0x40
	private GameObject _objInfoBtnEntryTeam; // 0x48
	private GameObject _objInfoBtnChessShopList; // 0x50
	private Action <onReturnClicked>k__BackingField; // 0x58
	private Action <onLeaveClicked>k__BackingField; // 0x60
	private CommonTopMenu m_commonTopMenu; // 0x68
	private static DelegateBridge __Hotfix0_get_onReturnClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onReturnClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onLeaveClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onLeaveClicked; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_EventOnReturnClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnLeaveClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action onReturnClicked { get; set; }
	private Action onLeaveClicked { get; set; }

	// RVA: 0x335f7c4 VA: 0x75959777c4
	private Action get_onReturnClicked() { }
	// RVA: 0x335f82c VA: 0x759597782c
	private Void set_onReturnClicked(Action value) { }
	// RVA: 0x335f8b0 VA: 0x75959778b0
	private Action get_onLeaveClicked() { }
	// RVA: 0x335f918 VA: 0x7595977918
	private Void set_onLeaveClicked(Action value) { }
	// RVA: 0x335f99c VA: 0x759597799c
	public Void Init(InputParams input) { }
	// RVA: 0x335fd00 VA: 0x7595977d00
	public Void EventOnReturnClick() { }
	// RVA: 0x335fd9c VA: 0x7595977d9c
	public Void EventOnLeaveClick() { }
	// RVA: 0x335fe38 VA: 0x7595977e38
	public Void .ctor() { }
}
```