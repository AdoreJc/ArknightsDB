# CampaignTemplateZoneMap

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `RectTransform _focusBound`

- `Image _imgBkg`

- `CampaignZoneStageBtn _stageMapObj`

- `UIStringEvent onStageClick`

- `Tween m_tween`

- `Single m_positionValue`

- `Single m_initValue`


## Methods

- `CampaignZoneStageBtn _GetStageButton(String, Boolean)`

- `Void RenderZoneId(CampaignZoneMapViewModel)`

- `Void RenderStageSelect(String)`

- `Void ApplyToPos(RectTransform)`

- `Void _FocusToValue(Single)`

- `Void _TraceForAVG(CampaignZoneStageBtn)`

- `Single <_FocusToValue>b__13_0()`

- `Void <_FocusToValue>b__13_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignTemplateZoneMap : MonoBehaviour, IHotfixable
{
	private List`1 _buttonContainerList; // 0x18
	private RectTransform _focusBound; // 0x20
	private Image _imgBkg; // 0x28
	private CampaignZoneStageBtn _stageMapObj; // 0x30
	public UIStringEvent onStageClick; // 0x38
	private List`1 m_btnList; // 0x40
	private Tween m_tween; // 0x48
	private Single m_positionValue; // 0x50
	private Single m_initValue; // 0x54
	private static DelegateBridge __Hotfix0__GetStageButton; // 0x0
	private static DelegateBridge __Hotfix0_RenderZoneId; // 0x8
	private static DelegateBridge __Hotfix0_RenderStageSelect; // 0x10
	private static DelegateBridge __Hotfix0_ApplyToPos; // 0x18
	private static DelegateBridge __Hotfix0__FocusToValue; // 0x20
	private static DelegateBridge __Hotfix0__TraceForAVG; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2e4a910 VA: 0x7595462910
	private CampaignZoneStageBtn _GetStageButton(String stageId, Boolean isCustomized) { }
	// RVA: 0x2e4aafc VA: 0x7595462afc
	public Void RenderZoneId(CampaignZoneMapViewModel zoneViewModel) { }
	// RVA: 0x2e4b604 VA: 0x7595463604
	public Void RenderStageSelect(String selectId) { }
	// RVA: 0x2e4b94c VA: 0x759546394c
	public Void ApplyToPos(RectTransform buttonTrans) { }
	// RVA: 0x2e4b724 VA: 0x7595463724
	public Void _FocusToValue(Single targetPos) { }
	// RVA: 0x2e4b508 VA: 0x7595463508
	private Void _TraceForAVG(CampaignZoneStageBtn stageObj) { }
	// RVA: 0x2e4bb34 VA: 0x7595463b34
	public Void .ctor() { }
	// RVA: 0x2e4bbf8 VA: 0x7595463bf8
	private Single <_FocusToValue>b__13_0() { }
	// RVA: 0x2e4bc00 VA: 0x7595463c00
	private Void <_FocusToValue>b__13_1(Single val) { }
}
```