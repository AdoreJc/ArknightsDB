# ConstructDetailedView

**Namespace:** `Torappu.Scripts.UI.ConstructLand`


## Fields

- `SandboxV2BuildingDetailPanel _buildingDetailPanel`

- `Color _detailedPanelColor`

- `UIAnimationLocation _animationSwitchTween`

- `Single _tweenDuration`

- `Toggle _detailDisplayToggle`

- `Sprite _repairAllInvalid`

- `Color _repairAllInvalidColor`

- `Sprite _repairValid`

- `Color _repairAllValidColor`

- `Image _repairImg`

- `Button _repairButton`

- `Text _goldRequired`

- `UIFadeFloatPanel _detailedHolder`

- `UIFadeFloatPanel _root`

- `SandboxV2BuildingDetailPanel m_detailedPanel`

- `AnimationSwitchTween m_switchTween`

- `Boolean m_rootIsHide`

- `OnRepairAllClicked onRepairAllClicked`

- `OnTipClicked onTipClicked`

- `SandboxV2ConstructDetailModel m_detailModel`


## Methods

- `Void InitIfNot(Param)`

- `Void Render(SandboxV2ConstructDetailModel)`

- `Void OnRepairAllBtnClicked()`

- `Void OnDetailTipClicked(SandboxV2ConstructTipType)`

- `Void OnToggleChanged()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.UI.ConstructLand
public class ConstructDetailedView : MonoBehaviour, IHotfixable
{
	private SandboxV2BuildingDetailPanel _buildingDetailPanel; // 0x18
	private Color _detailedPanelColor; // 0x20
	private UIAnimationLocation _animationSwitchTween; // 0x30
	private Single _tweenDuration; // 0x40
	private Toggle _detailDisplayToggle; // 0x48
	private Sprite _repairAllInvalid; // 0x50
	private Color _repairAllInvalidColor; // 0x58
	private Sprite _repairValid; // 0x68
	private Color _repairAllValidColor; // 0x70
	private Image _repairImg; // 0x80
	private Button _repairButton; // 0x88
	private Text _goldRequired; // 0x90
	private UIFadeFloatPanel _detailedHolder; // 0x98
	private UIFadeFloatPanel _root; // 0xa0
	private SandboxV2BuildingDetailPanel m_detailedPanel; // 0xa8
	private AnimationSwitchTween m_switchTween; // 0xb0
	private Boolean m_rootIsHide; // 0xb8
	private OnRepairAllClicked onRepairAllClicked; // 0xc0
	private OnTipClicked onTipClicked; // 0xc8
	private Action`1 onDetailedToggleClicked; // 0xd0
	private SandboxV2ConstructDetailModel m_detailModel; // 0xd8
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnRepairAllBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnDetailTipClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnToggleChanged; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x376fcf8 VA: 0x7595d87cf8
	public Void InitIfNot(Param param) { }
	// RVA: 0x376ff88 VA: 0x7595d87f88
	public Void Render(SandboxV2ConstructDetailModel model) { }
	// RVA: 0x3770168 VA: 0x7595d88168
	public Void OnRepairAllBtnClicked() { }
	// RVA: 0x37701f8 VA: 0x7595d881f8
	private Void OnDetailTipClicked(SandboxV2ConstructTipType tipType) { }
	// RVA: 0x3770298 VA: 0x7595d88298
	public Void OnToggleChanged() { }
	// RVA: 0x3770370 VA: 0x7595d88370
	public Void .ctor() { }
}
```