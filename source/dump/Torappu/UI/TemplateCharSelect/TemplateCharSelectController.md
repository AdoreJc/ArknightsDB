# TemplateCharSelectController

**Namespace:** `Torappu.UI.TemplateCharSelect`


## Fields

- `Transform _poolViewContainer`

- `Transform _shuffleViewContainer`

- `Transform _ensureContainer`

- `Transform _detailContainer`

- `TemplateCharSelectCardView m_charCardPrefab`

- `TemplateCharSelectPoolView m_poolView`

- `TemplateCharSelectDetailView m_detailView`

- `TemplateCharSelectShuffleView m_shuffleView`

- `TemplateCharSelectEnsureView m_ensureView`

- `ITemplateCharSelectCtrlHost m_host`


## Properties

- `TemplateCharSelectCardView charCardPrefab`


## Methods

- `Void TriggerResume()`

- `Boolean TryInitTemplateCharController(InputParam, ITemplateCharSelectCtrlHost, ITemplateCharSelectCustomization)`

- `Void ApplySelectInput(InputParam)`

- `Boolean _CheckPropValid()`

- `TemplateCharSelectCardView get_charCardPrefab()`

- `Void OnCharClick(Int32)`

- `Void OnEnsureClick()`

- `Void OnClearClick()`

- `Void NotifyUpdate()`

- `Void NotifyShuffleUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect
public class TemplateCharSelectController : MonoBehaviour, ITemplateCharSelectCtrl, IHotfixable
{
	private Transform _poolViewContainer; // 0x18
	private Transform _shuffleViewContainer; // 0x20
	private Transform _ensureContainer; // 0x28
	private Transform _detailContainer; // 0x30
	private TemplateCharSelectCardView m_charCardPrefab; // 0x38
	private TemplateCharSelectPoolView m_poolView; // 0x40
	private TemplateCharSelectDetailView m_detailView; // 0x48
	private TemplateCharSelectShuffleView m_shuffleView; // 0x50
	private TemplateCharSelectEnsureView m_ensureView; // 0x58
	private List`1 m_views; // 0x60
	private ITemplateCharSelectCtrlHost m_host; // 0x68
	private static DelegateBridge __Hotfix0_TriggerResume; // 0x0
	private static DelegateBridge __Hotfix0_TryInitTemplateCharController; // 0x8
	private static DelegateBridge __Hotfix0_ApplySelectInput; // 0x10
	private static DelegateBridge __Hotfix0__CheckPropValid; // 0x18
	private static DelegateBridge __Hotfix0_get_charCardPrefab; // 0x20
	private static DelegateBridge __Hotfix0_OnCharClick; // 0x28
	private static DelegateBridge __Hotfix0_OnEnsureClick; // 0x30
	private static DelegateBridge __Hotfix0_OnClearClick; // 0x38
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x40
	private static DelegateBridge __Hotfix0_NotifyShuffleUpdate; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public TemplateCharSelectCardView charCardPrefab { get; }

	// RVA: 0x2c4d294 VA: 0x7595265294
	public Void TriggerResume() { }
	// RVA: 0x2c4d4c0 VA: 0x75952654c0
	public Boolean TryInitTemplateCharController(InputParam inputParam, ITemplateCharSelectCtrlHost host, ITemplateCharSelectCustomization resHolder) { }
	// RVA: 0x2c4de28 VA: 0x7595265e28
	public Void ApplySelectInput(InputParam inputParam) { }
	// RVA: 0x2c4dcc4 VA: 0x7595265cc4
	private Boolean _CheckPropValid() { }
	// RVA: 0x2c4dfc8 VA: 0x7595265fc8
	public TemplateCharSelectCardView get_charCardPrefab() { }
	// RVA: 0x2c4e030 VA: 0x7595266030
	public Void OnCharClick(Int32 instId) { }
	// RVA: 0x2c4e2a4 VA: 0x75952662a4
	public Void OnEnsureClick() { }
	// RVA: 0x2c4e424 VA: 0x7595266424
	public Void OnClearClick() { }
	// RVA: 0x2c4e5cc VA: 0x75952665cc
	public Void NotifyUpdate() { }
	// RVA: 0x2c4e6dc VA: 0x75952666dc
	public Void NotifyShuffleUpdate() { }
	// RVA: 0x2c4e910 VA: 0x7595266910
	public Void .ctor() { }
}
```