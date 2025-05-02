# BossRushStageDetailTeamGroupView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `GameObject _panelBuffInfo`

- `TwoStateToggle _toggleBuffInfoEmpty`

- `Image _imgBuffIcon`

- `Text _textBuffName`

- `Text _textBuffDesc`

- `AnimationWrapper _infoAnimWrapper`

- `SimpleLayoutContent _teamItemContent`

- `ScrollRect _teamScrollRect`

- `HorizontalLayoutGroup _layoutGroup`

- `Single _scrollDuration`

- `String m_cachedSelectTeam`

- `BossRushStageType m_cachedStageType`

- `String m_cachedStageGroupId`

- `Boolean m_needRefreshAll`

- `Boolean m_hasInited`

- `String m_actId`

- `Adapter m_adapter`

- `TweenWrapper m_buffInfoTween`

- `Tween m_scrollTween`

- `Boolean <needReset>k__BackingField`


## Properties

- `Boolean needReset`


## Methods

- `Void set_onTeamClick(Action`1)`

- `Boolean get_needReset()`

- `Void set_needReset(Boolean)`

- `Void _GenerateScrollTween(Int32)`

- `Void _ScrollToItem(Int32)`

- `Void _RefreshBuffInfo()`

- `Void _RefreshBuffInfoContent()`

- `Void _InitIfNot()`

- `Single <_ScrollToItem>b__33_0()`

- `Void <_ScrollToItem>b__33_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailTeamGroupView : DataBinder`1, IHotfixable
{
	private const String INFO_HIDE_ANIM; // 0x0
	private const String INFO_SHOW_ANIM; // 0x0
	private GameObject _panelBuffInfo; // 0x20
	private TwoStateToggle _toggleBuffInfoEmpty; // 0x28
	private Image _imgBuffIcon; // 0x30
	private Text _textBuffName; // 0x38
	private Text _textBuffDesc; // 0x40
	private AnimationWrapper _infoAnimWrapper; // 0x48
	private SimpleLayoutContent _teamItemContent; // 0x50
	private ScrollRect _teamScrollRect; // 0x58
	private HorizontalLayoutGroup _layoutGroup; // 0x60
	private Single _scrollDuration; // 0x68
	private String m_cachedSelectTeam; // 0x70
	private List`1 m_cachedTeamList; // 0x78
	private BossRushStageType m_cachedStageType; // 0x80
	private String m_cachedStageGroupId; // 0x88
	private Boolean m_needRefreshAll; // 0x90
	private Boolean m_hasInited; // 0x91
	private String m_actId; // 0x98
	private Adapter m_adapter; // 0xa0
	private TweenWrapper m_buffInfoTween; // 0xa8
	private Tween m_scrollTween; // 0xb0
	private Action`1 <onTeamClick>k__BackingField; // 0xb8
	private Boolean <needReset>k__BackingField; // 0xc0
	private static DelegateBridge __Hotfix0_get_onTeamClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onTeamClick; // 0x8
	private static DelegateBridge __Hotfix0_get_needReset; // 0x10
	private static DelegateBridge __Hotfix0_set_needReset; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__GenerateScrollTween; // 0x28
	private static DelegateBridge __Hotfix0__ScrollToItem; // 0x30
	private static DelegateBridge __Hotfix0__RefreshBuffInfo; // 0x38
	private static DelegateBridge __Hotfix0__RefreshBuffInfoContent; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`1 onTeamClick { get; set; }
	private Boolean needReset { get; set; }

	// RVA: 0x2e7ae34 VA: 0x7595492e34
	private Action`1 get_onTeamClick() { }
	// RVA: 0x2e77dd8 VA: 0x759548fdd8
	public Void set_onTeamClick(Action`1 value) { }
	// RVA: 0x2e7ae9c VA: 0x7595492e9c
	private Boolean get_needReset() { }
	// RVA: 0x2e77e5c VA: 0x759548fe5c
	public Void set_needReset(Boolean value) { }
	// RVA: 0x2e7af04 VA: 0x7595492f04
	public override Void OnValueChanged(BossRushStageDetailProperty property) { }
	// RVA: 0x2e7b3a0 VA: 0x75954933a0
	private Void _GenerateScrollTween(Int32 position) { }
	// RVA: 0x2e7b52c VA: 0x759549352c
	private Void _ScrollToItem(Int32 position) { }
	// RVA: 0x2e7b1b8 VA: 0x75954931b8
	private Void _RefreshBuffInfo() { }
	// RVA: 0x2e7b854 VA: 0x7595493854
	private Void _RefreshBuffInfoContent() { }
	// RVA: 0x2e7b0e8 VA: 0x75954930e8
	private Void _InitIfNot() { }
	// RVA: 0x2e7ba5c VA: 0x7595493a5c
	public Void .ctor() { }
	// RVA: 0x2e7bb20 VA: 0x7595493b20
	private Single <_ScrollToItem>b__33_0() { }
	// RVA: 0x2e7bb3c VA: 0x7595493b3c
	private Void <_ScrollToItem>b__33_1(Single value) { }
}
```