# Act12sideMilestoneView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Act12sideMilestoneListAdapter _listAdapter`

- `Text _textPoint`

- `Text _textCompletion`

- `Button _btnGetReward`

- `Boolean m_hasInited`

- `String m_actId`

- `AudioClickPlayer m_btnGetRewardAudio`

- `Action <onAllMilestoneCallBack>k__BackingField`


## Properties

- `Action onAllMilestoneCallBack`


## Methods

- `Void set_onPhotoCallback(Action`1)`

- `Void set_onMilestoneCallBack(Action`1)`

- `Action get_onAllMilestoneCallBack()`

- `Void set_onAllMilestoneCallBack(Action)`

- `Void Init(String)`

- `Void UpdatePhotoWall()`

- `Void OnPhotoClick(PhotoInfo)`

- `Void _InitIfNot()`

- `Void OnBtnRewardAllClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMilestoneView : DataBinder`1
{
	private Act12sideMilestoneListAdapter _listAdapter; // 0x20
	private Text _textPoint; // 0x28
	private Text _textCompletion; // 0x30
	private Button _btnGetReward; // 0x38
	private Act12sidePhotoWallItemView[] _photoList; // 0x40
	private Boolean m_hasInited; // 0x48
	private String m_actId; // 0x50
	private AudioClickPlayer m_btnGetRewardAudio; // 0x58
	private Action`1 <onPhotoCallback>k__BackingField; // 0x60
	private Action`1 <onMilestoneCallBack>k__BackingField; // 0x68
	private Action <onAllMilestoneCallBack>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onPhotoCallback; // 0x0
	private static DelegateBridge __Hotfix0_set_onPhotoCallback; // 0x8
	private static DelegateBridge __Hotfix0_get_onMilestoneCallBack; // 0x10
	private static DelegateBridge __Hotfix0_set_onMilestoneCallBack; // 0x18
	private static DelegateBridge __Hotfix0_get_onAllMilestoneCallBack; // 0x20
	private static DelegateBridge __Hotfix0_set_onAllMilestoneCallBack; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge __Hotfix0_UpdatePhotoWall; // 0x40
	private static DelegateBridge __Hotfix0_OnPhotoClick; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnRewardAllClick; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Action`1 onPhotoCallback { get; set; }
	private Action`1 onMilestoneCallBack { get; set; }
	private Action onAllMilestoneCallBack { get; set; }

	// RVA: 0x3465e40 VA: 0x7595a7de40
	private Action`1 get_onPhotoCallback() { }
	// RVA: 0x345e010 VA: 0x7595a76010
	public Void set_onPhotoCallback(Action`1 value) { }
	// RVA: 0x3465ea8 VA: 0x7595a7dea8
	private Action`1 get_onMilestoneCallBack() { }
	// RVA: 0x345e094 VA: 0x7595a76094
	public Void set_onMilestoneCallBack(Action`1 value) { }
	// RVA: 0x3465f10 VA: 0x7595a7df10
	private Action get_onAllMilestoneCallBack() { }
	// RVA: 0x345e118 VA: 0x7595a76118
	public Void set_onAllMilestoneCallBack(Action value) { }
	// RVA: 0x345df8c VA: 0x7595a75f8c
	public Void Init(String actId) { }
	// RVA: 0x3465f78 VA: 0x7595a7df78
	public override Void OnValueChanged(Act12sideMilestoneProperty property) { }
	// RVA: 0x345db84 VA: 0x7595a75b84
	public Void UpdatePhotoWall() { }
	// RVA: 0x346646c VA: 0x7595a7e46c
	public Void OnPhotoClick(PhotoInfo photInfo) { }
	// RVA: 0x34661bc VA: 0x7595a7e1bc
	private Void _InitIfNot() { }
	// RVA: 0x3466524 VA: 0x7595a7e524
	public Void OnBtnRewardAllClick() { }
	// RVA: 0x34665c0 VA: 0x7595a7e5c0
	public Void .ctor() { }
}
```