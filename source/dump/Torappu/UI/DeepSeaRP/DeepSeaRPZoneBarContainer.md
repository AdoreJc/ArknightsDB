# DeepSeaRPZoneBarContainer

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `DeepSeaRPCoinView _coinView`

- `Text _txtCurZoneName`

- `UICommonTrackPoint _newArchiveTrackPoint`

- `GameObject _objTechPart`

- `GameObject _objNewTechNode`

- `Text _txtExploreProgress`

- `GameObject _objMissionProcessing`

- `GameObject _objMissionFree`

- `Text _txtMainlineId`

- `Text _txtMainlineDesc`

- `Text _txtMainlineFree`

- `GameObject _objTechUnlockTips`

- `CanvasGroup _canvasTechUnlockTips`

- `RectTransform _rectTechUnlockTips`

- `Text _txtTechUnlockTips`

- `String m_focusId`

- `Int32 m_toastSequence`

- `Action <onTechDetailClick>k__BackingField`

- `Action <onShopClick>k__BackingField`

- `Action <onArchiveClick>k__BackingField`

- `Action <onZoneSwitchClick>k__BackingField`

- `Boolean m_hasInited`

- `TechUnlockTipsPopTween m_techUnlockTipsTween`

- `TrackPointViewProperty m_newArchiveProperty`

- `Boolean m_isAct`


## Properties

- `Action onTechDetailClick`

- `Action onShopClick`

- `Action onArchiveClick`

- `Action onZoneSwitchClick`


## Methods

- `Action get_onTechDetailClick()`

- `Void set_onTechDetailClick(Action)`

- `Action get_onShopClick()`

- `Void set_onShopClick(Action)`

- `Action get_onArchiveClick()`

- `Void set_onArchiveClick(Action)`

- `Action get_onZoneSwitchClick()`

- `Void set_onZoneSwitchClick(Action)`

- `Void set_onMissionAimClick(Action`1)`

- `Void _TryTriggerAVG()`

- `Void EventOnShopClick()`

- `Void EventOnCollectionClick()`

- `Void EventOnTechNodesClick()`

- `Void EventOnZoneSwitchClick()`

- `Void EventOnMissionAimClick()`

- `Void _InitIfNot()`

- `Void _ShowTechPart(DeepSeaRPTechModel)`

- `Void _ShowTechUnlockTips(DeepSeaRPTechModel)`

- `Void _ShowMainlineProgress(DeepSeaRPModel)`

- `MainlineData _GetMainlineData(DeepSeaRPModel, out)`

- `String _TryFindFocusIdRecursively(DeepSeaRPModel, String, Dictionary`2)`

- `Boolean _IsNodeComplete(DeepSeaRPNodeModel)`

- `DeepSeaRPNodeModel _TryGetNodeModel(DeepSeaRPModel, String)`

- `Void _CalcExploreProgress(DeepSeaRPModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPZoneBarContainer : DataBinder`1
{
	private DeepSeaRPCoinView _coinView; // 0x20
	private Text _txtCurZoneName; // 0x28
	private UICommonTrackPoint _newArchiveTrackPoint; // 0x30
	private GameObject _objTechPart; // 0x38
	private GameObject _objNewTechNode; // 0x40
	private List`1 _techTreeViewList; // 0x48
	private Text _txtExploreProgress; // 0x50
	private GameObject _objMissionProcessing; // 0x58
	private GameObject _objMissionFree; // 0x60
	private Text _txtMainlineId; // 0x68
	private Text _txtMainlineDesc; // 0x70
	private Text _txtMainlineFree; // 0x78
	private GameObject _objTechUnlockTips; // 0x80
	private CanvasGroup _canvasTechUnlockTips; // 0x88
	private RectTransform _rectTechUnlockTips; // 0x90
	private Text _txtTechUnlockTips; // 0x98
	private String m_focusId; // 0xa0
	private Int32 m_toastSequence; // 0xa8
	private Action <onTechDetailClick>k__BackingField; // 0xb0
	private Action <onShopClick>k__BackingField; // 0xb8
	private Action <onArchiveClick>k__BackingField; // 0xc0
	private Action <onZoneSwitchClick>k__BackingField; // 0xc8
	private Action`1 <onMissionAimClick>k__BackingField; // 0xd0
	private Boolean m_hasInited; // 0xd8
	private TechUnlockTipsPopTween m_techUnlockTipsTween; // 0xe0
	private TrackPointViewProperty m_newArchiveProperty; // 0xe8
	private Boolean m_isAct; // 0xf0
	private static DelegateBridge __Hotfix0_get_onTechDetailClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onTechDetailClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onShopClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onShopClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onArchiveClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onArchiveClick; // 0x28
	private static DelegateBridge __Hotfix0_get_onZoneSwitchClick; // 0x30
	private static DelegateBridge __Hotfix0_set_onZoneSwitchClick; // 0x38
	private static DelegateBridge __Hotfix0_get_onMissionAimClick; // 0x40
	private static DelegateBridge __Hotfix0_set_onMissionAimClick; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0__TryTriggerAVG; // 0x58
	private static DelegateBridge __Hotfix0_EventOnShopClick; // 0x60
	private static DelegateBridge __Hotfix0_EventOnCollectionClick; // 0x68
	private static DelegateBridge __Hotfix0_EventOnTechNodesClick; // 0x70
	private static DelegateBridge __Hotfix0_EventOnZoneSwitchClick; // 0x78
	private static DelegateBridge __Hotfix0_EventOnMissionAimClick; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x88
	private static DelegateBridge __Hotfix0__ShowTechPart; // 0x90
	private static DelegateBridge __Hotfix0__ShowTechUnlockTips; // 0x98
	private static DelegateBridge __Hotfix0__ShowMainlineProgress; // 0xa0
	private static DelegateBridge __Hotfix0__GetMainlineData; // 0xa8
	private static DelegateBridge __Hotfix0__TryFindFocusIdRecursively; // 0xb0
	private static DelegateBridge __Hotfix0__IsNodeComplete; // 0xb8
	private static DelegateBridge __Hotfix0__TryGetNodeModel; // 0xc0
	private static DelegateBridge __Hotfix0__CalcExploreProgress; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	private Action onTechDetailClick { get; set; }
	private Action onShopClick { get; set; }
	private Action onArchiveClick { get; set; }
	private Action onZoneSwitchClick { get; set; }
	private Action`1 onMissionAimClick { get; set; }

	// RVA: 0x29cc1d0 VA: 0x7594fe41d0
	private Action get_onTechDetailClick() { }
	// RVA: 0x29cc238 VA: 0x7594fe4238
	public Void set_onTechDetailClick(Action value) { }
	// RVA: 0x29cc2bc VA: 0x7594fe42bc
	private Action get_onShopClick() { }
	// RVA: 0x29cc324 VA: 0x7594fe4324
	public Void set_onShopClick(Action value) { }
	// RVA: 0x29cc3a8 VA: 0x7594fe43a8
	private Action get_onArchiveClick() { }
	// RVA: 0x29cc410 VA: 0x7594fe4410
	public Void set_onArchiveClick(Action value) { }
	// RVA: 0x29cc494 VA: 0x7594fe4494
	private Action get_onZoneSwitchClick() { }
	// RVA: 0x29cc4fc VA: 0x7594fe44fc
	public Void set_onZoneSwitchClick(Action value) { }
	// RVA: 0x29cc580 VA: 0x7594fe4580
	private Action`1 get_onMissionAimClick() { }
	// RVA: 0x29cc5e8 VA: 0x7594fe45e8
	public Void set_onMissionAimClick(Action`1 value) { }
	// RVA: 0x29cc66c VA: 0x7594fe466c
	public override Void OnValueChanged(DeepSeaRPProperty property) { }
	// RVA: 0x29cd308 VA: 0x7594fe5308
	private Void _TryTriggerAVG() { }
	// RVA: 0x29cd3c4 VA: 0x7594fe53c4
	public Void EventOnShopClick() { }
	// RVA: 0x29cd46c VA: 0x7594fe546c
	public Void EventOnCollectionClick() { }
	// RVA: 0x29cd514 VA: 0x7594fe5514
	public Void EventOnTechNodesClick() { }
	// RVA: 0x29cd5bc VA: 0x7594fe55bc
	public Void EventOnZoneSwitchClick() { }
	// RVA: 0x29cd664 VA: 0x7594fe5664
	public Void EventOnMissionAimClick() { }
	// RVA: 0x29cc920 VA: 0x7594fe4920
	private Void _InitIfNot() { }
	// RVA: 0x29ccbf4 VA: 0x7594fe4bf4
	private Void _ShowTechPart(DeepSeaRPTechModel techModel) { }
	// RVA: 0x29cdac0 VA: 0x7594fe5ac0
	private Void _ShowTechUnlockTips(DeepSeaRPTechModel techModel) { }
	// RVA: 0x29cd200 VA: 0x7594fe5200
	private Void _ShowMainlineProgress(DeepSeaRPModel deepSeaRpModel) { }
	// RVA: 0x29cdc44 VA: 0x7594fe5c44
	private MainlineData _GetMainlineData(DeepSeaRPModel deepSeaModel, out Boolean isFree) { }
	// RVA: 0x29ce250 VA: 0x7594fe6250
	private String _TryFindFocusIdRecursively(DeepSeaRPModel deepSeaModel, String nodeId, Dictionary`2 nodeFocusDic) { }
	// RVA: 0x29ce478 VA: 0x7594fe6478
	private Boolean _IsNodeComplete(DeepSeaRPNodeModel node) { }
	// RVA: 0x29ce120 VA: 0x7594fe6120
	private DeepSeaRPNodeModel _TryGetNodeModel(DeepSeaRPModel deepSeaModel, String nodeId) { }
	// RVA: 0x29ccd8c VA: 0x7594fe4d8c
	private Void _CalcExploreProgress(DeepSeaRPModel deepSeaModel) { }
	// RVA: 0x29ce82c VA: 0x7594fe682c
	public Void .ctor() { }
}
```