# Act20sideRecycleView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Text _recycleNum`

- `Text _goldNum`

- `Button _confirmBtn`

- `Button _cancelBtn`

- `UIBlurFloatPanel _blurBg`

- `String m_activityId`

- `Boolean m_hasInited`

- `Coroutine _hideCoroutine`

- `Coroutine _claimCoroutine`


## Methods

- `Void Render(Act20sideMilestoneViewModel)`

- `Void OnCancel()`

- `Void Hide()`

- `Void OnRecycleClick()`

- `Void _InitIfNot()`

- `IEnumerator _ReceiveItemsCoroutine(List`1, Action)`

- `Void <OnRecycleClick>b__12_0(ClaimMilestoneAwardResponse)`

- `Void <OnRecycleClick>b__12_1()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideRecycleView : PageSingleComponent
{
	private Text _recycleNum; // 0x20
	private Text _goldNum; // 0x28
	private Button _confirmBtn; // 0x30
	private Button _cancelBtn; // 0x38
	private UIBlurFloatPanel _blurBg; // 0x40
	private String m_activityId; // 0x48
	private Boolean m_hasInited; // 0x50
	private Coroutine _hideCoroutine; // 0x58
	private Coroutine _claimCoroutine; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnCancel; // 0x8
	private static DelegateBridge __Hotfix0_Hide; // 0x10
	private static DelegateBridge __Hotfix0_OnRecycleClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x32fa0f4 VA: 0x75959120f4
	public Void Render(Act20sideMilestoneViewModel viewModel) { }
	// RVA: 0x3300f28 VA: 0x7595918f28
	public Void OnCancel() { }
	// RVA: 0x3300f90 VA: 0x7595918f90
	private Void Hide() { }
	// RVA: 0x3301004 VA: 0x7595919004
	public Void OnRecycleClick() { }
	// RVA: 0x3300dc0 VA: 0x7595918dc0
	private Void _InitIfNot() { }
	// RVA: 0x33011ec VA: 0x75959191ec
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList, Action onConfirm) { }
	// RVA: 0x33012ec VA: 0x75959192ec
	public Void .ctor() { }
	// RVA: 0x330135c VA: 0x759591935c
	private Void <OnRecycleClick>b__12_0(ClaimMilestoneAwardResponse response) { }
	// RVA: 0x3301428 VA: 0x7595919428
	private Void <OnRecycleClick>b__12_1() { }
}
```