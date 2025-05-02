# Act24sideMissionDetailView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `GameObject _bigLogoHunter`

- `GameObject _bigLogoCollection`

- `GameObject _bigLogoExploration`

- `GameObject _completeBtn`

- `UIAtlasImage _missionContent`

- `Text _missionTitle`

- `Text _missionDesc`

- `Text _missionClient`

- `Text _missionClientDesc`

- `Act24sideMissionStampView _stampView`

- `Act24sideMissionDelegateTitleView _titleView`

- `Act24sideMissionRewardListView _rewardListView`

- `UIAnimationLocation _leftAnimationLocation`

- `UIAnimationLocation _rightAnimationLocation`

- `Single _renderDelay`

- `Color _missionHunterContentColor`

- `Color _missionCollectionContentColor`

- `Color _missionExplorationContentColor`

- `GameObject _leftArrow`

- `GameObject _rightArrow`

- `Button _leftBtn`

- `Button _rightBtn`

- `String m_missionId`

- `Int32 m_cachePos`

- `Int32 m_missionTotalCnt`

- `Int32 m_sequenceNum`

- `Sequence m_moveSequence`

- `Act24sideMissionViewModel m_cacheModel`

- `UIStateFinder m_stateFinder`

- `Action onClickLeftArrowBtn`

- `Action onClickRightArrowBtn`


## Methods

- `Void _Render()`

- `Void _UpdateArrowDisplay()`

- `Void _MoveLeft()`

- `Void _MoveRight()`

- `Void _SetBtnStateEnable()`

- `Void _SetBtnStateUnable()`

- `Void OnClickLeftArrow()`

- `Void OnClickRightArrow()`

- `Void OnClickCompleteBtn()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionDetailView : DataBinder`1
{
	private GameObject _bigLogoHunter; // 0x20
	private GameObject _bigLogoCollection; // 0x28
	private GameObject _bigLogoExploration; // 0x30
	private GameObject _completeBtn; // 0x38
	private UIAtlasImage _missionContent; // 0x40
	private Text _missionTitle; // 0x48
	private Text _missionDesc; // 0x50
	private Text _missionClient; // 0x58
	private Text _missionClientDesc; // 0x60
	private Act24sideMissionStampView _stampView; // 0x68
	private Act24sideMissionDelegateTitleView _titleView; // 0x70
	private Act24sideMissionRewardListView _rewardListView; // 0x78
	private UIAnimationLocation _leftAnimationLocation; // 0x80
	private UIAnimationLocation _rightAnimationLocation; // 0x90
	private Single _renderDelay; // 0xa0
	private Color _missionHunterContentColor; // 0xa4
	private Color _missionCollectionContentColor; // 0xb4
	private Color _missionExplorationContentColor; // 0xc4
	private GameObject _leftArrow; // 0xd8
	private GameObject _rightArrow; // 0xe0
	private Button _leftBtn; // 0xe8
	private Button _rightBtn; // 0xf0
	private String m_missionId; // 0xf8
	private Int32 m_cachePos; // 0x100
	private Int32 m_missionTotalCnt; // 0x104
	private Int32 m_sequenceNum; // 0x108
	private Sequence m_moveSequence; // 0x110
	private Act24sideMissionViewModel m_cacheModel; // 0x118
	private UIStateFinder m_stateFinder; // 0x120
	public Action`1 onClickCompleteBtn; // 0x130
	public Action onClickLeftArrowBtn; // 0x138
	public Action onClickRightArrowBtn; // 0x140
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__UpdateArrowDisplay; // 0x10
	private static DelegateBridge __Hotfix0__MoveLeft; // 0x18
	private static DelegateBridge __Hotfix0__MoveRight; // 0x20
	private static DelegateBridge __Hotfix0__SetBtnStateEnable; // 0x28
	private static DelegateBridge __Hotfix0__SetBtnStateUnable; // 0x30
	private static DelegateBridge __Hotfix0_OnClickLeftArrow; // 0x38
	private static DelegateBridge __Hotfix0_OnClickRightArrow; // 0x40
	private static DelegateBridge __Hotfix0_OnClickCompleteBtn; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x32b6c54 VA: 0x75958cec54
	public override Void OnValueChanged(Act24sideMissionDetailProp property) { }
	// RVA: 0x32b6e04 VA: 0x75958cee04
	private Void _Render() { }
	// RVA: 0x32b7564 VA: 0x75958cf564
	private Void _UpdateArrowDisplay() { }
	// RVA: 0x32b72d0 VA: 0x75958cf2d0
	private Void _MoveLeft() { }
	// RVA: 0x32b703c VA: 0x75958cf03c
	private Void _MoveRight() { }
	// RVA: 0x32b6d84 VA: 0x75958ced84
	private Void _SetBtnStateEnable() { }
	// RVA: 0x32b78ec VA: 0x75958cf8ec
	private Void _SetBtnStateUnable() { }
	// RVA: 0x32b796c VA: 0x75958cf96c
	public Void OnClickLeftArrow() { }
	// RVA: 0x32b79fc VA: 0x75958cf9fc
	public Void OnClickRightArrow() { }
	// RVA: 0x32b7a94 VA: 0x75958cfa94
	public Void OnClickCompleteBtn() { }
	// RVA: 0x32b7b38 VA: 0x75958cfb38
	public Void .ctor() { }
}
```