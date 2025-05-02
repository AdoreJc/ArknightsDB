# CampaignFeeControlView

**Namespace:** `Torappu.UI.Stage.Campaign`


## Fields

- `Text _feeRefreshCountDownText`

- `Text _feeProgressText`

- `Slider _feeProgressSlider`

- `RectTransform _notFullHint`

- `Single _unitWidthOfTotalFee`

- `Single _minPanelWidth`

- `CanvasGroup m_canvasGroup`

- `RectTransform m_rectTransform`

- `FadeSwitchTween m_fadeSwitch`

- `CampaignZoneViewModel m_campZoneModel`


## Methods

- `Void _SetVisibility(Boolean)`

- `Void _SetPanelWidth(CampaignZoneViewModel)`

- `Void _SetData(CampaignZoneViewModel)`

- `Void _UpdateNextRefreshDateTime()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.Campaign
public class CampaignFeeControlView : DataBinder`1
{
	private Text _feeRefreshCountDownText; // 0x20
	private Text _feeProgressText; // 0x28
	private Slider _feeProgressSlider; // 0x30
	private RectTransform _notFullHint; // 0x38
	private Single _unitWidthOfTotalFee; // 0x40
	private Single _minPanelWidth; // 0x44
	private CanvasGroup m_canvasGroup; // 0x48
	private RectTransform m_rectTransform; // 0x50
	private FadeSwitchTween m_fadeSwitch; // 0x58
	private CampaignZoneViewModel m_campZoneModel; // 0x60
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__SetVisibility; // 0x8
	private static DelegateBridge __Hotfix0__SetPanelWidth; // 0x10
	private static DelegateBridge __Hotfix0__SetData; // 0x18
	private static DelegateBridge __Hotfix0__UpdateNextRefreshDateTime; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2fe0d4c VA: 0x75955f8d4c
	public override Void OnValueChanged(ZoneViewProperty property) { }
	// RVA: 0x2fe0f14 VA: 0x75955f8f14
	private Void _SetVisibility(Boolean isVisible) { }
	// RVA: 0x2fe1080 VA: 0x75955f9080
	private Void _SetPanelWidth(CampaignZoneViewModel campZoneModel) { }
	// RVA: 0x2fe11b4 VA: 0x75955f91b4
	private Void _SetData(CampaignZoneViewModel campZoneModel) { }
	// RVA: 0x2fe14b0 VA: 0x75955f94b0
	private Void _UpdateNextRefreshDateTime() { }
	// RVA: 0x2fe1768 VA: 0x75955f9768
	private Void Update() { }
	// RVA: 0x2fe17d0 VA: 0x75955f97d0
	public Void .ctor() { }
}
```