# TemplateMissionCommonItemNormalView

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `Single _preferSize`

- `SimpleLayoutContent _content`

- `Single _rewardItemScalerFactor`

- `Text _missionDetail`

- `Color _colMissionDetailCanClaim`

- `Color _colMissionDetailNormal`

- `Slider _progressSlider`

- `Text _progressDetail`

- `UIAtlasImage _imgCanClaimThemeBg`

- `GameObject _panelCountRemain`

- `Text _textCountRemain`

- `GameObject _panelEndRemain`

- `Text _textEndRemain`

- `Boolean m_isInited`

- `RewardAdapter m_adapter`

- `TemplateMissionListNormalItemViewModel m_cachedViewModel`

- `AbstractTemplateMissionRewardItemView m_rewardItemViewPrefab`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(TemplateMissionNormalItemVirtualViewStruct)`

- `Void _InitIfNot()`

- `Void _SetPartsActiveByState()`

- `Void _RenderMissionProgressInfo()`

- `Void _RenderMissionThemePart()`

- `Void _RenderRewardPart()`

- `Void _RenderMissionDescriptionPart()`

- `Void _RenderMissionRemainPart()`

- `Void OnMissionItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionCommonItemNormalView : AbstractTemplateMissionItemNormalView
{
	private Single _preferSize; // 0x18
	private SimpleLayoutContent _content; // 0x20
	private Single _rewardItemScalerFactor; // 0x28
	private List`1 _canClaimPart; // 0x30
	private List`1 _cannotGetPart; // 0x38
	private List`1 _claimedPart; // 0x40
	private Text _missionDetail; // 0x48
	private Color _colMissionDetailCanClaim; // 0x50
	private Color _colMissionDetailNormal; // 0x60
	private Slider _progressSlider; // 0x70
	private Text _progressDetail; // 0x78
	private UIAtlasImage _imgCanClaimThemeBg; // 0x80
	private GameObject _panelCountRemain; // 0x88
	private Text _textCountRemain; // 0x90
	private GameObject _panelEndRemain; // 0x98
	private Text _textEndRemain; // 0xa0
	private Boolean m_isInited; // 0xa8
	private RewardAdapter m_adapter; // 0xb0
	private TemplateMissionListNormalItemViewModel m_cachedViewModel; // 0xb8
	private AbstractTemplateMissionRewardItemView m_rewardItemViewPrefab; // 0xc0
	private List`1 m_itemViewModelList; // 0xc8
	private UIStateFinder m_stateFinder; // 0xd0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__SetPartsActiveByState; // 0x10
	private static DelegateBridge __Hotfix0__RenderMissionProgressInfo; // 0x18
	private static DelegateBridge __Hotfix0__RenderMissionThemePart; // 0x20
	private static DelegateBridge __Hotfix0__RenderRewardPart; // 0x28
	private static DelegateBridge __Hotfix0__RenderMissionDescriptionPart; // 0x30
	private static DelegateBridge __Hotfix0__RenderMissionRemainPart; // 0x38
	private static DelegateBridge __Hotfix0_OnMissionItemClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x23652b8 VA: 0x759497d2b8
	public Void Render(TemplateMissionNormalItemVirtualViewStruct viewStruct) { }
	// RVA: 0x2365468 VA: 0x759497d468
	private Void _InitIfNot() { }
	// RVA: 0x236553c VA: 0x759497d53c
	private Void _SetPartsActiveByState() { }
	// RVA: 0x2365838 VA: 0x759497d838
	private Void _RenderMissionProgressInfo() { }
	// RVA: 0x236570c VA: 0x759497d70c
	private Void _RenderMissionThemePart() { }
	// RVA: 0x23659d0 VA: 0x759497d9d0
	private Void _RenderRewardPart() { }
	// RVA: 0x2365a68 VA: 0x759497da68
	private Void _RenderMissionDescriptionPart() { }
	// RVA: 0x2365b64 VA: 0x759497db64
	private Void _RenderMissionRemainPart() { }
	// RVA: 0x2365ce0 VA: 0x759497dce0
	public Void OnMissionItemClick() { }
	// RVA: 0x2365e20 VA: 0x759497de20
	public Void .ctor() { }
}
```