# SixStarStagePreviewRuneBarView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `GameObject _panelLock`

- `TwoStateToggle _validToggle`

- `UICommonTrackPoint _advanceTrackPoint`

- `StageSixStarRuneStatus m_cachedSixStarRuneStatus`

- `Boolean m_cachedIsAdvanceTagUnlocked`

- `UIStateFinder m_uiStateFinder`

- `TrackPointViewProperty m_pointViewProperty`


## Methods

- `Void Render(IStageSelectHandler, StageViewModel)`

- `Boolean _CheckIfAdvanceTagUnlocked(StageViewModel)`

- `Void OnTagSwitchBtnClick()`

- `Void OnSelectRuneBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarStagePreviewRuneBarView : MonoBehaviour, IHotfixable
{
	private GameObject _panelLock; // 0x18
	private TwoStateToggle _validToggle; // 0x20
	private UICommonTrackPoint _advanceTrackPoint; // 0x28
	private StageSixStarRuneStatus m_cachedSixStarRuneStatus; // 0x30
	private Boolean m_cachedIsAdvanceTagUnlocked; // 0x34
	private UIStateFinder m_uiStateFinder; // 0x38
	private TrackPointViewProperty m_pointViewProperty; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__CheckIfAdvanceTagUnlocked; // 0x8
	private static DelegateBridge __Hotfix0_OnTagSwitchBtnClick; // 0x10
	private static DelegateBridge __Hotfix0_OnSelectRuneBtnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f4c448 VA: 0x7595564448
	public Void Render(IStageSelectHandler zoneModel, StageViewModel stageModel) { }
	// RVA: 0x2f4c610 VA: 0x7595564610
	private Boolean _CheckIfAdvanceTagUnlocked(StageViewModel stageModel) { }
	// RVA: 0x2f4c6d4 VA: 0x75955646d4
	public Void OnTagSwitchBtnClick() { }
	// RVA: 0x2f4c81c VA: 0x759556481c
	public Void OnSelectRuneBtnClick() { }
	// RVA: 0x2f4c8c8 VA: 0x75955648c8
	public Void .ctor() { }
}
```