# StageZoneHomeClimbTowerToDoItem

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _textOfferLowerItemName`

- `Text _textOfferHigherItemName`

- `Text _textOfferLowerItemProgress`

- `Text _textOfferHigherItemProgress`

- `Slider _sliderOfferLowerItemProgress`

- `Slider _sliderOfferHigherItemProgress`

- `Text _textTowerName`

- `TwoStateToggle _toggleInBatlleImg`

- `Sprite _mainBg`

- `String _feeProgressFormat`

- `TwoStateToggle _toggleInBattle`


## Methods

- `Void _RenderCurrentView(ClimbTowerModel)`

- `Void _RenderOfferView(ClimbTowerModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeClimbTowerToDoItem : StageZoneHomeToDoItemPlugin
{
	private Text _textOfferLowerItemName; // 0x28
	private Text _textOfferHigherItemName; // 0x30
	private Text _textOfferLowerItemProgress; // 0x38
	private Text _textOfferHigherItemProgress; // 0x40
	private Slider _sliderOfferLowerItemProgress; // 0x48
	private Slider _sliderOfferHigherItemProgress; // 0x50
	private Text _textTowerName; // 0x58
	private TwoStateToggle _toggleInBatlleImg; // 0x60
	private Sprite _mainBg; // 0x68
	public String _feeProgressFormat; // 0x70
	private TwoStateToggle _toggleInBattle; // 0x78
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x0
	private static DelegateBridge __Hotfix0_LoadMainSprite; // 0x8
	private static DelegateBridge __Hotfix0__RenderCurrentView; // 0x10
	private static DelegateBridge __Hotfix0__RenderOfferView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2f0f1ac VA: 0x75955271ac
	protected override Void OnDataUpdated() { }
	// RVA: 0x2f0f590 VA: 0x7595527590
	protected override Sprite LoadMainSprite() { }
	// RVA: 0x2f0f2c0 VA: 0x75955272c0
	private Void _RenderCurrentView(ClimbTowerModel towerModel) { }
	// RVA: 0x2f0f36c VA: 0x759552736c
	private Void _RenderOfferView(ClimbTowerModel towerModel) { }
	// RVA: 0x2f0f5f8 VA: 0x75955275f8
	public Void .ctor() { }
}
```