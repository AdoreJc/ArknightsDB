# Act1VAutoChessChessShopDetailView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `RectTransform _detailPanelContainer`

- `Act1VAutoChessCharSelectDetailPanel _detailPanelPrefab`

- `Button _backBtn`

- `TwoStateToggle _assistBtn`

- `Image _assistHead`

- `Act1VAutoChessCharSelectDetailPanel m_detailPanel`

- `UIStateFinder m_stateFinder`


## Methods

- `Void RenderViewModel(Act1VAutoChessChessShopViewModel)`

- `Void _SetCharName(String)`

- `Void _InitIfNot()`

- `Void EventOnBack()`

- `Void EventOnConfirmCharDetailClick()`

- `Void EventOnFriendAssist()`

- `Void SelectEquip(String)`

- `Void SelectSkill(String)`

- `Void SwitchGold(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopDetailView : MonoBehaviour, IHotfixable, ICtrl
{
	private RectTransform _detailPanelContainer; // 0x18
	private Act1VAutoChessCharSelectDetailPanel _detailPanelPrefab; // 0x20
	private Button _backBtn; // 0x28
	private TwoStateToggle _assistBtn; // 0x30
	private Text[] _assistName; // 0x38
	private Image _assistHead; // 0x40
	private Act1VAutoChessCharSelectDetailPanel m_detailPanel; // 0x48
	private UIStateFinder m_stateFinder; // 0x50
	private static DelegateBridge __Hotfix0_RenderViewModel; // 0x0
	private static DelegateBridge __Hotfix0__SetCharName; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBack; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirmCharDetailClick; // 0x20
	private static DelegateBridge __Hotfix0_EventOnFriendAssist; // 0x28
	private static DelegateBridge __Hotfix0_SelectEquip; // 0x30
	private static DelegateBridge __Hotfix0_SelectSkill; // 0x38
	private static DelegateBridge __Hotfix0_SwitchGold; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3312dec VA: 0x759592adec
	public Void RenderViewModel(Act1VAutoChessChessShopViewModel model) { }
	// RVA: 0x33132c0 VA: 0x759592b2c0
	private Void _SetCharName(String name) { }
	// RVA: 0x33130cc VA: 0x759592b0cc
	private Void _InitIfNot() { }
	// RVA: 0x33133f4 VA: 0x759592b3f4
	public Void EventOnBack() { }
	// RVA: 0x3313498 VA: 0x759592b498
	public Void EventOnConfirmCharDetailClick() { }
	// RVA: 0x331353c VA: 0x759592b53c
	public Void EventOnFriendAssist() { }
	// RVA: 0x33135e0 VA: 0x759592b5e0
	public Void SelectEquip(String equipId) { }
	// RVA: 0x33136dc VA: 0x759592b6dc
	public Void SelectSkill(String skillId) { }
	// RVA: 0x33137d8 VA: 0x759592b7d8
	public Void SwitchGold(Boolean isGold) { }
	// RVA: 0x33138d8 VA: 0x759592b8d8
	public Void .ctor() { }
}
```