# Act1LockMissionItem

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Image _bg`

- `Sprite _doingBg`

- `Sprite _doneBg`

- `GameObject _doneGlow`

- `GameObject _completeMask`

- `Text _descText`

- `Text _prgText`

- `Slider _prgBar`

- `GameObject _prgRoot`

- `RectTransform _rewardCellRoot`

- `Mission m_mission`

- `Status m_status`


## Methods

- `Void add_eClick(Action`1)`

- `Void remove_eClick(Action`1)`

- `Void Flush(Mission)`

- `Void _ChangeStatus(Status)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockMissionItem : MonoBehaviour, IHotfixable
{
	private Image _bg; // 0x18
	private Sprite _doingBg; // 0x20
	private Sprite _doneBg; // 0x28
	private GameObject _doneGlow; // 0x30
	private GameObject _completeMask; // 0x38
	private Text _descText; // 0x40
	private Text _prgText; // 0x48
	private Slider _prgBar; // 0x50
	private GameObject _prgRoot; // 0x58
	private RectTransform _rewardCellRoot; // 0x60
	private Mission m_mission; // 0x68
	private Action`1 eClick; // 0x70
	private Status m_status; // 0x78
	private static DelegateBridge __Hotfix0_add_eClick; // 0x0
	private static DelegateBridge __Hotfix0_remove_eClick; // 0x8
	private static DelegateBridge __Hotfix0_Flush; // 0x10
	private static DelegateBridge __Hotfix0__ChangeStatus; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x33d0a00 VA: 0x75959e8a00
	public Void add_eClick(Action`1 value) { }
	// RVA: 0x33d0af4 VA: 0x75959e8af4
	public Void remove_eClick(Action`1 value) { }
	// RVA: 0x33d0be8 VA: 0x75959e8be8
	public Void Flush(Mission mission) { }
	// RVA: 0x33d10d4 VA: 0x75959e90d4
	private Void _ChangeStatus(Status status) { }
	// RVA: 0x33d11cc VA: 0x75959e91cc
	public Void EventOnClick() { }
	// RVA: 0x33d1274 VA: 0x75959e9274
	public Void .ctor() { }
}
```