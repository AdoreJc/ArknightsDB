# Act1LockMilestoneItem

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Image _bg`

- `Sprite _completedBg`

- `Sprite _uncompletedBg`

- `GameObject _grow`

- `GameObject _getedMask`

- `GameObject _descBg`

- `Color _white`

- `Color _blue`

- `Text _needCnt`

- `Text _needDesc`

- `Text _rewardName`

- `Text _rewardCnt`

- `RectTransform _rewardIconRoot`

- `MileStoneItemInfo <itemInfo>k__BackingField`

- `Status <status>k__BackingField`


## Properties

- `MileStoneItemInfo itemInfo`

- `Status status`


## Methods

- `MileStoneItemInfo get_itemInfo()`

- `Void set_itemInfo(MileStoneItemInfo)`

- `Status get_status()`

- `Void set_status(Status)`

- `Void Init(MileStoneItemInfo, UIItemViewModel, Action`1)`

- `Void UpdateStatus(Int32, Boolean)`

- `Void EventOnClick()`

- `Void ChangeStatus(Status)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockMilestoneItem : MonoBehaviour, IHotfixable
{
	private Image _bg; // 0x18
	private Sprite _completedBg; // 0x20
	private Sprite _uncompletedBg; // 0x28
	private GameObject _grow; // 0x30
	private GameObject _getedMask; // 0x38
	private GameObject _descBg; // 0x40
	private Color _white; // 0x48
	private Color _blue; // 0x58
	private Text _needCnt; // 0x68
	private Text _needDesc; // 0x70
	private Text _rewardName; // 0x78
	private Text _rewardCnt; // 0x80
	private RectTransform _rewardIconRoot; // 0x88
	private MileStoneItemInfo <itemInfo>k__BackingField; // 0x90
	private Action`1 m_getFunc; // 0x98
	private Status <status>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_itemInfo; // 0x0
	private static DelegateBridge __Hotfix0_set_itemInfo; // 0x8
	private static DelegateBridge __Hotfix0_get_status; // 0x10
	private static DelegateBridge __Hotfix0_set_status; // 0x18
	private static DelegateBridge __Hotfix0_Init; // 0x20
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x28
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x30
	private static DelegateBridge __Hotfix0_ChangeStatus; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public MileStoneItemInfo itemInfo { get; set; }
	public Status status { get; set; }

	// RVA: 0x33d0010 VA: 0x75959e8010
	public MileStoneItemInfo get_itemInfo() { }
	// RVA: 0x33d0078 VA: 0x75959e8078
	private Void set_itemInfo(MileStoneItemInfo value) { }
	// RVA: 0x33d00fc VA: 0x75959e80fc
	public Status get_status() { }
	// RVA: 0x33d0164 VA: 0x75959e8164
	private Void set_status(Status value) { }
	// RVA: 0x33d01e0 VA: 0x75959e81e0
	public Void Init(MileStoneItemInfo msitem, UIItemViewModel point, Action`1 getfunc) { }
	// RVA: 0x33d0608 VA: 0x75959e8608
	public Void UpdateStatus(Int32 pointCnt, Boolean getted) { }
	// RVA: 0x33d08b0 VA: 0x75959e88b0
	public Void EventOnClick() { }
	// RVA: 0x33d06b8 VA: 0x75959e86b8
	public Void ChangeStatus(Status newStatus) { }
	// RVA: 0x33d0958 VA: 0x75959e8958
	public Void .ctor() { }
}
```