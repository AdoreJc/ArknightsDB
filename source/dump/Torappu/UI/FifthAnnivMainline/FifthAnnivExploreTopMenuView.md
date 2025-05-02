# FifthAnnivExploreTopMenuView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `RectTransform _dynViewContainer`

- `FifthAnnivExploreTopMenuHeritageView _heritageViewPrefab`

- `FifthAnnivExploreTopMenuProgressView _progressViewPrefab`

- `UICommonTrackPoint _missionTrackpoint`

- `Action <onHeritageBtnClick>k__BackingField`

- `Action <onProgressBtnClick>k__BackingField`

- `Boolean m_isInited`

- `FifthAnnivExploreTopMenuHeritageView m_heritageView`

- `FifthAnnivExploreTopMenuProgressView m_progressView`

- `TrackPointViewProperty m_missionTrackPointViewProperty`


## Properties

- `Action onHeritageBtnClick`

- `Action onProgressBtnClick`


## Methods

- `Void set_onHeritageBtnClick(Action)`

- `Action get_onHeritageBtnClick()`

- `Void set_onProgressBtnClick(Action)`

- `Action get_onProgressBtnClick()`

- `Void _OnHeritageBtnClick()`

- `Void _OnProgressBtnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreTopMenuView : DataBinder`1, IHotfixable
{
	private RectTransform _dynViewContainer; // 0x20
	private FifthAnnivExploreTopMenuHeritageView _heritageViewPrefab; // 0x28
	private FifthAnnivExploreTopMenuProgressView _progressViewPrefab; // 0x30
	private UICommonTrackPoint _missionTrackpoint; // 0x38
	private Action <onHeritageBtnClick>k__BackingField; // 0x40
	private Action <onProgressBtnClick>k__BackingField; // 0x48
	private Boolean m_isInited; // 0x50
	private FifthAnnivExploreTopMenuHeritageView m_heritageView; // 0x58
	private FifthAnnivExploreTopMenuProgressView m_progressView; // 0x60
	private TrackPointViewProperty m_missionTrackPointViewProperty; // 0x68
	private static DelegateBridge __Hotfix0_set_onHeritageBtnClick; // 0x0
	private static DelegateBridge __Hotfix0_get_onHeritageBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_set_onProgressBtnClick; // 0x10
	private static DelegateBridge __Hotfix0_get_onProgressBtnClick; // 0x18
	private static DelegateBridge __Hotfix0__OnHeritageBtnClick; // 0x20
	private static DelegateBridge __Hotfix0__OnProgressBtnClick; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action onHeritageBtnClick { get; set; }
	private Action onProgressBtnClick { get; set; }

	// RVA: 0x29331e0 VA: 0x7594f4b1e0
	public Void set_onHeritageBtnClick(Action value) { }
	// RVA: 0x2933264 VA: 0x7594f4b264
	private Action get_onHeritageBtnClick() { }
	// RVA: 0x29332cc VA: 0x7594f4b2cc
	public Void set_onProgressBtnClick(Action value) { }
	// RVA: 0x2933350 VA: 0x7594f4b350
	private Action get_onProgressBtnClick() { }
	// RVA: 0x29333b8 VA: 0x7594f4b3b8
	private Void _OnHeritageBtnClick() { }
	// RVA: 0x2933454 VA: 0x7594f4b454
	private Void _OnProgressBtnClick() { }
	// RVA: 0x29334f0 VA: 0x7594f4b4f0
	private Void _InitIfNot() { }
	// RVA: 0x2933720 VA: 0x7594f4b720
	public override Void OnValueChanged(FifthAnnivExploreProperty property) { }
	// RVA: 0x2933874 VA: 0x7594f4b874
	public Void .ctor() { }
}
```