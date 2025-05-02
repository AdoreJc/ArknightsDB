# SandboxV2RacerInventoryInfoView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2RacerInventoryDetailView _prefabDetail`

- `RectTransform _containerDetail`

- `GameObject _panelStartBattle`

- `GameObject _hotSpotStartBattle`

- `GameObject _panelStartBattleDisable`

- `Text _textApCost`

- `GameObject _panelRelease`

- `GameObject _panelBtnTempBag`

- `Text _textTempBagName`

- `Slider _progressTempBag`

- `GameObject _panelTempBagFullTip`

- `Boolean m_hasInited`

- `SandboxV2RacerInventoryDetailView m_detailView`

- `UIStateFinder m_stateFinder`


## Methods

- `Void EventOnReleaseClicked()`

- `Void EventOnStartBattleClicked()`

- `Void EventOnTempBagClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RacerInventoryInfoView : DataBinder`1, IHotfixable
{
	private const String AP_COST_FORMAT; // 0x0
	private SandboxV2RacerInventoryDetailView _prefabDetail; // 0x20
	private RectTransform _containerDetail; // 0x28
	private GameObject _panelStartBattle; // 0x30
	private GameObject _hotSpotStartBattle; // 0x38
	private GameObject _panelStartBattleDisable; // 0x40
	private Text _textApCost; // 0x48
	private GameObject _panelRelease; // 0x50
	private GameObject _panelBtnTempBag; // 0x58
	private Text _textTempBagName; // 0x60
	private Slider _progressTempBag; // 0x68
	private GameObject _panelTempBagFullTip; // 0x70
	private Boolean m_hasInited; // 0x78
	private SandboxV2RacerInventoryDetailView m_detailView; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnReleaseClicked; // 0x8
	private static DelegateBridge __Hotfix0_EventOnStartBattleClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnTempBagClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x25e18dc VA: 0x7594bf98dc
	public override Void OnValueChanged(SandboxV2RacerInventoryProperty property) { }
	// RVA: 0x25e1c18 VA: 0x7594bf9c18
	public Void EventOnReleaseClicked() { }
	// RVA: 0x25e1cbc VA: 0x7594bf9cbc
	public Void EventOnStartBattleClicked() { }
	// RVA: 0x25e1d60 VA: 0x7594bf9d60
	public Void EventOnTempBagClicked() { }
	// RVA: 0x25e1b30 VA: 0x7594bf9b30
	private Void _InitIfNot() { }
	// RVA: 0x25e1e04 VA: 0x7594bf9e04
	public Void .ctor() { }
}
```