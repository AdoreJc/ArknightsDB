# AutoChessShopTrapHudPlugin

**Namespace:** `Torappu.Battle`


## Fields

- `Text _chessLevelText`

- `GameObject _root`

- `GameObject _levelRoot`

- `GameObject _coinRoot`

- `Image _coinImg`

- `Sprite _coinNotEnoughSprite`

- `Sprite _coinEnoughSprite`

- `Text _coinText`

- `Color _colorEnough`

- `Color _colorNotEnough`

- `CoinDisplayType m_coinDisplayType`

- `Boolean m_hideCoinWhenLevelMax`

- `Boolean m_displayLevel`

- `Int32 m_currentLevel`

- `Int32 m_coinAmount`

- `Boolean m_isCoinDisplayedEnough`


## Methods

- `Void _UpdateInternal(Object)`

- `Void _UpdateCoinDisplay(Boolean, Boolean)`

- `Void _UpdateCoinAmount(Int32, Boolean)`

- `Void <>xLuaBaseProxy_DoAttach(Unit, UIPluginTalent)`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AutoChessShopTrapHudPlugin : UnitTalentUIPlugin
{
	private Text _chessLevelText; // 0x30
	private GameObject _root; // 0x38
	private GameObject _levelRoot; // 0x40
	private GameObject _coinRoot; // 0x48
	private Image _coinImg; // 0x50
	private Sprite _coinNotEnoughSprite; // 0x58
	private Sprite _coinEnoughSprite; // 0x60
	private Text _coinText; // 0x68
	private Color _colorEnough; // 0x70
	private Color _colorNotEnough; // 0x80
	private List`1 _utilTrapSettings; // 0x90
	private CoinDisplayType m_coinDisplayType; // 0x98
	private Boolean m_hideCoinWhenLevelMax; // 0x9c
	private Boolean m_displayLevel; // 0x9d
	private Int32 m_currentLevel; // 0xa0
	private Int32 m_coinAmount; // 0xa4
	private Boolean m_isCoinDisplayedEnough; // 0xa8
	private const String SHOP_LEVEL_FORMAT; // 0x0
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_DoDetach; // 0x8
	private static DelegateBridge __Hotfix0__UpdateInternal; // 0x10
	private static DelegateBridge __Hotfix0__UpdateCoinDisplay; // 0x18
	private static DelegateBridge __Hotfix0__UpdateCoinAmount; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1b88930 VA: 0x75941a0930
	protected override Void DoAttach(Unit owner, UIPluginTalent talent) { }
	// RVA: 0x1b89058 VA: 0x75941a1058
	protected override Void DoDetach() { }
	// RVA: 0x1b891fc VA: 0x75941a11fc
	private Void _UpdateInternal(Object arg) { }
	// RVA: 0x1b88e60 VA: 0x75941a0e60
	private Void _UpdateCoinDisplay(Boolean isEnough, Boolean force) { }
	// RVA: 0x1b88f84 VA: 0x75941a0f84
	private Void _UpdateCoinAmount(Int32 amount, Boolean force) { }
	// RVA: 0x1b893f4 VA: 0x75941a13f4
	public Void .ctor() { }
	// RVA: 0x1b89534 VA: 0x75941a1534
	private Void <>xLuaBaseProxy_DoAttach(Unit P0, UIPluginTalent P1) { }
	// RVA: 0x1b89538 VA: 0x75941a1538
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```