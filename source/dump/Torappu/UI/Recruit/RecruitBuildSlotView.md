# RecruitBuildSlotView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _textSlotNum`

- `GameObject _panelBuilding`

- `GameObject _panelEmpty`

- `GameObject _panelLock`

- `GameObject _panelFinish`

- `Text _textRemainTime`

- `RecruitBuildTagGroupView _requireTagGroup`

- `RecruitBuildTagGroupView _resultTagGroup`

- `RecruitBuildCostView _costView`

- `Text _textLockedView`

- `Int32 m_slotIndexCache`

- `CountDownTask m_realTimeCountDown`

- `CountDownTask m_showTimeCountDown`


## Methods

- `Void Render(BuildSlotViewModel)`

- `Boolean RegisterEmptySlotForAVG()`

- `Void _RenderResultView(BuildSlotViewModel)`

- `Void _OnSlotStateChanged(BuildSlotViewModel, Nullable`1, Nullable`1)`

- `Void Update()`

- `Void _RenderBuildingView(BuildSlotViewModel)`

- `Void OnBuildTimeUp()`

- `Void OnFashFinish()`

- `Void OnStopRecruit()`

- `Void OnStartRecruit()`

- `Void OnFinishBuild()`

- `Void OnBuySlot()`

- `Void <_RenderBuildingView>b__27_0(TickValue)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuildSlotView : MonoBehaviour, IHotfixable
{
	private Text _textSlotNum; // 0x18
	private GameObject _panelBuilding; // 0x20
	private GameObject _panelEmpty; // 0x28
	private GameObject _panelLock; // 0x30
	private GameObject _panelFinish; // 0x38
	private Text _textRemainTime; // 0x40
	private RecruitBuildTagGroupView _requireTagGroup; // 0x48
	private RecruitBuildTagGroupView _resultTagGroup; // 0x50
	private RecruitBuildCostView _costView; // 0x58
	private Text _textLockedView; // 0x60
	public Action`1 fastFinishListener; // 0x68
	public Action`1 stopRecruitListener; // 0x70
	public Action`1 startRecruitListener; // 0x78
	public Action`1 buildTimeUpListener; // 0x80
	public Action`1 finishBuildListener; // 0x88
	public Action`1 buySlotListener; // 0x90
	private Int32 m_slotIndexCache; // 0x98
	private Nullable`1 m_slotStateCache; // 0x9c
	private BuildTagModel[] m_requireTagsCache; // 0xa8
	private BuildTagModel[] m_resultTagsCache; // 0xb0
	private CountDownTask m_realTimeCountDown; // 0xb8
	private CountDownTask m_showTimeCountDown; // 0xc0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RegisterEmptySlotForAVG; // 0x8
	private static DelegateBridge __Hotfix0__RenderResultView; // 0x10
	private static DelegateBridge __Hotfix0__OnSlotStateChanged; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0__RenderBuildingView; // 0x28
	private static DelegateBridge __Hotfix0_OnBuildTimeUp; // 0x30
	private static DelegateBridge __Hotfix0_OnFashFinish; // 0x38
	private static DelegateBridge __Hotfix0_OnStopRecruit; // 0x40
	private static DelegateBridge __Hotfix0_OnStartRecruit; // 0x48
	private static DelegateBridge __Hotfix0_OnFinishBuild; // 0x50
	private static DelegateBridge __Hotfix0_OnBuySlot; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x2705f84 VA: 0x7594d1df84
	public Void Render(BuildSlotViewModel viewModel) { }
	// RVA: 0x2706318 VA: 0x7594d1e318
	public Boolean RegisterEmptySlotForAVG() { }
	// RVA: 0x27067b0 VA: 0x7594d1e7b0
	private Void _RenderResultView(BuildSlotViewModel viewModel) { }
	// RVA: 0x2706490 VA: 0x7594d1e490
	private Void _OnSlotStateChanged(BuildSlotViewModel viewModel, Nullable`1 prev, Nullable`1 current) { }
	// RVA: 0x270686c VA: 0x7594d1e86c
	private Void Update() { }
	// RVA: 0x2706580 VA: 0x7594d1e580
	private Void _RenderBuildingView(BuildSlotViewModel viewModel) { }
	// RVA: 0x27068f8 VA: 0x7594d1e8f8
	private Void OnBuildTimeUp() { }
	// RVA: 0x2706994 VA: 0x7594d1e994
	public Void OnFashFinish() { }
	// RVA: 0x2706a1c VA: 0x7594d1ea1c
	public Void OnStopRecruit() { }
	// RVA: 0x2706aa4 VA: 0x7594d1eaa4
	public Void OnStartRecruit() { }
	// RVA: 0x2706b2c VA: 0x7594d1eb2c
	public Void OnFinishBuild() { }
	// RVA: 0x2706bb4 VA: 0x7594d1ebb4
	public Void OnBuySlot() { }
	// RVA: 0x2706c3c VA: 0x7594d1ec3c
	public Void .ctor() { }
	// RVA: 0x2706cb4 VA: 0x7594d1ecb4
	private Void <_RenderBuildingView>b__27_0(TickValue val) { }
}
```