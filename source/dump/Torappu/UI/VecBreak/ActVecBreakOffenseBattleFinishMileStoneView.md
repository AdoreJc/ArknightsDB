# ActVecBreakOffenseBattleFinishMileStoneView

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `Slider _mileStoneProgressSlider`

- `Text _mileStoneLevelText`

- `Text _mileStoneCurrentProgressText`

- `Text _mileStoneTotalProgressText`

- `Text _mileStoneTokenRewardText`

- `GameObject _mileStoneMaxLevelTag`

- `Image _mileStoneTokenIcon`

- `Single _mileStoneAnimTime`

- `Single _mileStoneWaitForNextTime`

- `ActVecBreakOffenseBattleFinishViewModel m_viewModel`

- `Int32 m_curTweenValue`

- `Int32 m_curTweenDestValue`

- `VecBreakMileStoneLevelData m_curTweenLevelData`


## Methods

- `Void OnRender(ActVecBreakOffenseBattleFinishViewModel)`

- `Void OnMileStoneTweenShow()`

- `Void _LoadMileStone(ActVecBreakData, PlayerVecBreakActivity)`

- `Sprite _LoadItemIcon(String)`

- `IEnumerator _TweenToTarget(String, Int32, Int32)`

- `Void _SetProgressText(Boolean, Int32, Int32)`

- `Int32 _GetMileStoneSliderValue()`

- `Void _SetMileStoneSliderValue(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class ActVecBreakOffenseBattleFinishMileStoneView : MonoBehaviour, IHotfixable
{
	private Slider _mileStoneProgressSlider; // 0x18
	private Text _mileStoneLevelText; // 0x20
	private Text _mileStoneCurrentProgressText; // 0x28
	private Text _mileStoneTotalProgressText; // 0x30
	private Text _mileStoneTokenRewardText; // 0x38
	private GameObject _mileStoneMaxLevelTag; // 0x40
	private Image _mileStoneTokenIcon; // 0x48
	private Single _mileStoneAnimTime; // 0x50
	private Single _mileStoneWaitForNextTime; // 0x54
	private ActVecBreakOffenseBattleFinishViewModel m_viewModel; // 0x58
	private Int32 m_curTweenValue; // 0x60
	private Int32 m_curTweenDestValue; // 0x64
	private VecBreakMileStoneLevelData m_curTweenLevelData; // 0x68
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_OnMileStoneTweenShow; // 0x8
	private static DelegateBridge __Hotfix0__LoadMileStone; // 0x10
	private static DelegateBridge __Hotfix0__LoadItemIcon; // 0x18
	private static DelegateBridge __Hotfix0__TweenToTarget; // 0x20
	private static DelegateBridge __Hotfix0__SetProgressText; // 0x28
	private static DelegateBridge __Hotfix0__GetMileStoneSliderValue; // 0x30
	private static DelegateBridge __Hotfix0__SetMileStoneSliderValue; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x22c47f0 VA: 0x75948dc7f0
	public Void OnRender(ActVecBreakOffenseBattleFinishViewModel viewModel) { }
	// RVA: 0x22c4b8c VA: 0x75948dcb8c
	public Void OnMileStoneTweenShow() { }
	// RVA: 0x22c48c4 VA: 0x75948dc8c4
	private Void _LoadMileStone(ActVecBreakData vecBreakData, PlayerVecBreakActivity activityData) { }
	// RVA: 0x22c4e68 VA: 0x75948dce68
	private Sprite _LoadItemIcon(String itemId) { }
	// RVA: 0x22c4c4c VA: 0x75948dcc4c
	private IEnumerator _TweenToTarget(String actId, Int32 srcBp, Int32 destBp) { }
	// RVA: 0x22c4d40 VA: 0x75948dcd40
	private Void _SetProgressText(Boolean isMaxLevel, Int32 curProgress, Int32 totalProgress) { }
	// RVA: 0x22c4fe8 VA: 0x75948dcfe8
	private Int32 _GetMileStoneSliderValue() { }
	// RVA: 0x22c5050 VA: 0x75948dd050
	private Void _SetMileStoneSliderValue(Int32 v) { }
	// RVA: 0x22c511c VA: 0x75948dd11c
	public Void .ctor() { }
}
```