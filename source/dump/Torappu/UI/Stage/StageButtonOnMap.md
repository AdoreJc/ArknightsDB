# StageButtonOnMap

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _stageNameText`

- `Text _stageCodeText`

- `StageRankViewViaSwitch _stageRank`

- `RectTransform _stageRankHolder`

- `UIColorGraphic _stageRankColorGraphic`

- `GameObject _apProtectPrefab`

- `TwoStateToggle m_selectionToggle`

- `RectTransform m_transform`

- `Boolean m_isInited`

- `Boolean m_isStageLocked`

- `GameObject m_extraItem`

- `String m_cacheDropId`

- `Boolean m_cacheShowApProtect`

- `ViewModelCache m_viewModelCache`

- `Events m_buttonEvents`

- `PluginBridge m_pluginBridge`

- `StageRankViewViaSwitch m_specialStageRank`

- `RankViewType m_rankViewType`

- `Boolean <isBlockClick>k__BackingField`


## Properties

- `Boolean isBlockClick`

- `Boolean isActive`

- `StageRankViewViaSwitch stageRankView`

- `Text stageNameText`

- `Text stageCodeText`

- `Boolean isStageLocked`

- `String stageId`


## Methods

- `Boolean get_isBlockClick()`

- `Void set_isBlockClick(Boolean)`

- `Boolean get_isActive()`

- `StageRankViewViaSwitch get_stageRankView()`

- `Text get_stageNameText()`

- `Text get_stageCodeText()`

- `Boolean get_isStageLocked()`

- `Void _InitIfNot()`

- `Void OnStageClick()`

- `Void InjectButtonEvents(Events)`

- `Void set_onPluginClick(Action`1)`

- `String get_stageId()`

- `PluginBridge PluginOnlyGetBridge()`

- `Void _TryShowRankView(RankViewType)`

- `Void _RenderTimelyDropAndApProtect(Boolean, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageButtonOnMap : MonoBehaviour, IHotfixable
{
	private Text _stageNameText; // 0x18
	private Text _stageCodeText; // 0x20
	private StageRankViewViaSwitch _stageRank; // 0x28
	private RectTransform _stageRankHolder; // 0x30
	private UIColorGraphic _stageRankColorGraphic; // 0x38
	private GameObject _apProtectPrefab; // 0x40
	private TwoStateToggle m_selectionToggle; // 0x48
	private RectTransform m_transform; // 0x50
	private Boolean m_isInited; // 0x58
	private Boolean m_isStageLocked; // 0x59
	private GameObject m_extraItem; // 0x60
	private String m_cacheDropId; // 0x68
	private Boolean m_cacheShowApProtect; // 0x70
	private ViewModelCache m_viewModelCache; // 0x78
	private Action`1 m_onPluginClickCallback; // 0xa0
	private Action`1 m_onClickCallback; // 0xa8
	private Events m_buttonEvents; // 0xb0
	private PluginBridge m_pluginBridge; // 0xc0
	private StageRankViewViaSwitch m_specialStageRank; // 0xc8
	private RankViewType m_rankViewType; // 0xd0
	private Boolean <isBlockClick>k__BackingField; // 0xd4
	private static DelegateBridge __Hotfix0_get_isBlockClick; // 0x0
	private static DelegateBridge __Hotfix0_set_isBlockClick; // 0x8
	private static DelegateBridge __Hotfix0_get_isActive; // 0x10
	private static DelegateBridge __Hotfix0_get_positionRect; // 0x18
	private static DelegateBridge __Hotfix0_get_stageRankView; // 0x20
	private static DelegateBridge __Hotfix0_get_stageNameText; // 0x28
	private static DelegateBridge __Hotfix0_get_stageCodeText; // 0x30
	private static DelegateBridge __Hotfix0_get_isStageLocked; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0_OnStageClick; // 0x48
	private static DelegateBridge __Hotfix0_TryLockStage; // 0x50
	private static DelegateBridge __Hotfix0_CheckIsStageButtonBlockClick; // 0x58
	private static DelegateBridge __Hotfix0_CheckStageLocked; // 0x60
	private static DelegateBridge __Hotfix0_InjectButtonEvents; // 0x68
	private static DelegateBridge __Hotfix0_set_onPluginClick; // 0x70
	private static DelegateBridge __Hotfix0_get_onPluginClick; // 0x78
	private static DelegateBridge __Hotfix0_get_stageId; // 0x80
	private static DelegateBridge __Hotfix0_PluginOnlyGetBridge; // 0x88
	private static DelegateBridge __Hotfix0_RenderStage; // 0x90
	private static DelegateBridge __Hotfix0__TryShowRankView; // 0x98
	private static DelegateBridge __Hotfix0__RenderTimelyDropAndApProtect; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public Boolean isBlockClick { get; set; }
	public Boolean isActive { get; }
	public virtual RectTransform positionRect { get; }
	protected StageRankViewViaSwitch stageRankView { get; }
	protected Text stageNameText { get; }
	protected Text stageCodeText { get; }
	protected Boolean isStageLocked { get; }
	public Action`1 onPluginClick { get; set; }
	public String stageId { get; }

	// RVA: 0x2fa1480 VA: 0x75955b9480
	public Boolean get_isBlockClick() { }
	// RVA: 0x2fa14e8 VA: 0x75955b94e8
	protected Void set_isBlockClick(Boolean value) { }
	// RVA: 0x2fa1568 VA: 0x75955b9568
	public Boolean get_isActive() { }
	// RVA: 0x2fa15e4 VA: 0x75955b95e4
	public virtual RectTransform get_positionRect() { }
	// RVA: 0x2fa16bc VA: 0x75955b96bc
	protected StageRankViewViaSwitch get_stageRankView() { }
	// RVA: 0x2fa1734 VA: 0x75955b9734
	protected Text get_stageNameText() { }
	// RVA: 0x2fa179c VA: 0x75955b979c
	protected Text get_stageCodeText() { }
	// RVA: 0x2fa1804 VA: 0x75955b9804
	protected Boolean get_isStageLocked() { }
	// RVA: 0x2fa186c VA: 0x75955b986c
	private Void _InitIfNot() { }
	// RVA: 0x2fa1948 VA: 0x75955b9948
	public Void OnStageClick() { }
	// RVA: 0x2fa19dc VA: 0x75955b99dc
	protected virtual Boolean TryLockStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x2fa1a94 VA: 0x75955b9a94
	protected virtual Boolean CheckIsStageButtonBlockClick(StageViewModel stageViewModel, ZoneViewModel zoneViewModel) { }
	// RVA: 0x2fa1b14 VA: 0x75955b9b14
	protected virtual Boolean CheckStageLocked(StageViewModel stageViewModel, ZoneViewModel zoneViewModel) { }
	// RVA: 0x2fa1bac VA: 0x75955b9bac
	public Void InjectButtonEvents(Events events) { }
	// RVA: 0x2fa1c3c VA: 0x75955b9c3c
	public Void set_onPluginClick(Action`1 value) { }
	// RVA: 0x2fa1cc0 VA: 0x75955b9cc0
	public Action`1 get_onPluginClick() { }
	// RVA: 0x2fa1d28 VA: 0x75955b9d28
	public String get_stageId() { }
	// RVA: 0x2fa1120 VA: 0x75955b9120
	public PluginBridge PluginOnlyGetBridge() { }
	// RVA: 0x2fa1dc0 VA: 0x75955b9dc0
	public virtual Void RenderStage(StageButtonOnMapHolder holder, StageViewModel viewModel, ZoneViewModel zoneViewModel, Boolean isSelected) { }
	// RVA: 0x2fa2274 VA: 0x75955ba274
	private Void _TryShowRankView(RankViewType rankViewType) { }
	// RVA: 0x2fa2854 VA: 0x75955ba854
	private Void _RenderTimelyDropAndApProtect(Boolean showApProtect, String timelyDropId) { }
	// RVA: 0x2fa2b7c VA: 0x75955bab7c
	public Void .ctor() { }
}
```