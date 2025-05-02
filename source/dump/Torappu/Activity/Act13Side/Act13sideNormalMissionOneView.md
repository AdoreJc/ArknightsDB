# Act13sideNormalMissionOneView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `TemplateActivityMissionItem _item`

- `Transform _container1`

- `Transform _container2`

- `SimpleLayoutContent _content`

- `Act13sidePrestigeProgressView _progressView`

- `Transform _progressViewContainer`

- `UICommonTrackPoint _longTermTrackPoint`

- `TrackPointViewProperty m_longTermTrackPointProperty`

- `Act13sidePrestigeProgressView m_progressView`

- `OrgAdapter m_adapter`

- `UIStringEvent receiveClick`

- `TemplateActivityMissionItem m_item1`

- `TemplateActivityMissionItem m_item2`

- `Boolean m_initFlag`

- `String m_groupId1`

- `String m_groupId2`


## Methods

- `Void _InitIfNot()`

- `Void OnViewModelRefresh(TemplateActivityViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideNormalMissionOneView : MonoBehaviour, IBaseActViewBinder, IHotfixable
{
	private const Single ANIM_FRAME_COUNT; // 0x0
	private const String FADE_IN_PARAM; // 0x0
	private const String FADE_OUT_PARAM; // 0x0
	private TemplateActivityMissionItem _item; // 0x18
	private Transform _container1; // 0x20
	private Transform _container2; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private Act13sidePrestigeProgressView _progressView; // 0x38
	private Transform _progressViewContainer; // 0x40
	private UICommonTrackPoint _longTermTrackPoint; // 0x48
	private TrackPointViewProperty m_longTermTrackPointProperty; // 0x50
	private Act13sidePrestigeProgressView m_progressView; // 0x58
	private OrgAdapter m_adapter; // 0x60
	public Action`1 missionGroupClick; // 0x68
	public Action`1 receiveAllMissionGroupClick; // 0x70
	public UIStringEvent receiveClick; // 0x78
	private TemplateActivityMissionItem m_item1; // 0x80
	private TemplateActivityMissionItem m_item2; // 0x88
	private Boolean m_initFlag; // 0x90
	private String m_groupId1; // 0x98
	private String m_groupId2; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnViewModelRefresh; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3431ff0 VA: 0x7595a49ff0
	private Void _InitIfNot() { }
	// RVA: 0x34323c0 VA: 0x7595a4a3c0
	public Void OnViewModelRefresh(TemplateActivityViewModel viewModel) { }
	// RVA: 0x3433528 VA: 0x7595a4b528
	public Void .ctor() { }
}
```