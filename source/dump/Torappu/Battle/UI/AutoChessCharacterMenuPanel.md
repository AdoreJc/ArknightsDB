# AutoChessCharacterMenuPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Single _focusRatio`

- `AutoChessGameMode m_gamemode`

- `AutoChessCharacterMenuButton _menuButton`

- `Canvas _rootCanvas`

- `String _underframePanelPrefabPath`

- `Sprite _withdrawTrapIcon`

- `Boolean m_inited`

- `Tile m_tile`

- `UIBattleUnderframePanel m_underframePanel`

- `Boolean m_needUpdateIfValid`

- `Boolean m_needResetCam`

- `GameState m_showState`


## Properties

- `AutoChessGameMode gamemode`

- `UIBattleUnderframePanel underframePanel`


## Methods

- `AutoChessGameMode get_gamemode()`

- `UIBattleUnderframePanel get_underframePanel()`

- `Void InitIfNot()`

- `Void Show(Character)`

- `Void Update()`

- `Void _DoRender(Character)`

- `Void _RenderHand(Character)`

- `Void _RenderBattleField(Character, Tile)`

- `Void _RenderShopItem(Character, Tile)`

- `Void _RenderDestoryMagic(Character)`

- `Void _RenderSellCharacter(String, Character)`

- `Void _RenderFreezeButton(UtilButtonConfig)`

- `Void _RenderRefreshButton(UtilButtonConfig)`

- `Void _RenderUpgradeButton(UtilButtonConfig)`

- `Void Hide()`

- `Void _OnSellClicked()`

- `Void _OnUpgradeClicked()`

- `Void _OnFreezeOrUnFreezeClicked()`

- `Void _OnBuyClicked()`

- `Void _OnRefreshClicked()`

- `Void _OnWithdrawClicked()`

- `Void _OnDestroyClicked()`

- `Boolean _IsUtilTrapValid()`

- `Boolean _IsUpgradeValid()`

- `Boolean _IsRefreshValid()`

- `Boolean _IsBuyValid()`

- `Boolean _IsSellOrDestoryValid()`

- `Boolean _CheckUtilFastClicked(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessCharacterMenuPanel : MonoBehaviour, IUICharacterMenuPanel, IHotfixable
{
	private Single _focusRatio; // 0x18
	private const Single FAST_CLICK_SWALLOW_TIME; // 0x0
	private const String COMMON_CLICK_KEY; // 0x0
	private AutoChessGameMode m_gamemode; // 0x20
	private AutoChessCharacterMenuButton _menuButton; // 0x28
	private Canvas _rootCanvas; // 0x30
	private String _underframePanelPrefabPath; // 0x38
	private Sprite _withdrawTrapIcon; // 0x40
	private Boolean m_inited; // 0x48
	private ListDict`2 m_lastClick; // 0x50
	private ObjectPtr`1 m_character; // 0x58
	private Tile m_tile; // 0x68
	private UIBattleUnderframePanel m_underframePanel; // 0x70
	private Dictionary`2 m_utilTrapHanders; // 0x78
	private Boolean m_needUpdateIfValid; // 0x80
	private Boolean m_needResetCam; // 0x81
	private GameState m_showState; // 0x84
	private static DelegateBridge __Hotfix0_get_gamemode; // 0x0
	private static DelegateBridge __Hotfix0_get_underframePanel; // 0x8
	private static DelegateBridge __Hotfix0_get_utilTrapHanders; // 0x10
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_Show; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge __Hotfix0__DoRender; // 0x30
	private static DelegateBridge __Hotfix0__RenderHand; // 0x38
	private static DelegateBridge __Hotfix0__RenderBattleField; // 0x40
	private static DelegateBridge __Hotfix0__RenderShopItem; // 0x48
	private static DelegateBridge __Hotfix0__RenderDestoryMagic; // 0x50
	private static DelegateBridge __Hotfix0__RenderSellCharacter; // 0x58
	private static DelegateBridge __Hotfix0__RenderFreezeButton; // 0x60
	private static DelegateBridge __Hotfix0__RenderRefreshButton; // 0x68
	private static DelegateBridge __Hotfix0__RenderUpgradeButton; // 0x70
	private static DelegateBridge __Hotfix0_Hide; // 0x78
	private static DelegateBridge __Hotfix0__OnSellClicked; // 0x80
	private static DelegateBridge __Hotfix0__OnUpgradeClicked; // 0x88
	private static DelegateBridge __Hotfix0__OnFreezeOrUnFreezeClicked; // 0x90
	private static DelegateBridge __Hotfix0__OnBuyClicked; // 0x98
	private static DelegateBridge __Hotfix0__OnRefreshClicked; // 0xa0
	private static DelegateBridge __Hotfix0__OnWithdrawClicked; // 0xa8
	private static DelegateBridge __Hotfix0__OnDestroyClicked; // 0xb0
	private static DelegateBridge __Hotfix0__IsUtilTrapValid; // 0xb8
	private static DelegateBridge __Hotfix0__IsUpgradeValid; // 0xc0
	private static DelegateBridge __Hotfix0__IsRefreshValid; // 0xc8
	private static DelegateBridge __Hotfix0__IsBuyValid; // 0xd0
	private static DelegateBridge __Hotfix0__IsSellOrDestoryValid; // 0xd8
	private static DelegateBridge __Hotfix0__CheckUtilFastClicked; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	private AutoChessGameMode gamemode { get; }
	private UIBattleUnderframePanel underframePanel { get; }
	private Dictionary`2 utilTrapHanders { get; }

	// RVA: 0x201b6d4 VA: 0x75946336d4
	private AutoChessGameMode get_gamemode() { }
	// RVA: 0x201b784 VA: 0x7594633784
	private UIBattleUnderframePanel get_underframePanel() { }
	// RVA: 0x201b968 VA: 0x7594633968
	private Dictionary`2 get_utilTrapHanders() { }
	// RVA: 0x201be3c VA: 0x7594633e3c
	private Void InitIfNot() { }
	// RVA: 0x201bfcc VA: 0x7594633fcc
	public Void Show(Character character) { }
	// RVA: 0x201c4f0 VA: 0x75946344f0
	public Void Update() { }
	// RVA: 0x201c054 VA: 0x7594634054
	private Void _DoRender(Character character) { }
	// RVA: 0x201ce24 VA: 0x7594634e24
	private Void _RenderHand(Character character) { }
	// RVA: 0x201c7d8 VA: 0x75946347d8
	private Void _RenderBattleField(Character character, Tile tile) { }
	// RVA: 0x201cae4 VA: 0x7594634ae4
	private Void _RenderShopItem(Character character, Tile tile) { }
	// RVA: 0x201cf88 VA: 0x7594634f88
	private Void _RenderDestoryMagic(Character character) { }
	// RVA: 0x201d160 VA: 0x7594635160
	private Void _RenderSellCharacter(String chessId, Character character) { }
	// RVA: 0x201d598 VA: 0x7594635598
	private Void _RenderFreezeButton(UtilButtonConfig config) { }
	// RVA: 0x201d83c VA: 0x759463583c
	private Void _RenderRefreshButton(UtilButtonConfig config) { }
	// RVA: 0x201db78 VA: 0x7594635b78
	private Void _RenderUpgradeButton(UtilButtonConfig config) { }
	// RVA: 0x201c680 VA: 0x7594634680
	public Void Hide() { }
	// RVA: 0x201dfcc VA: 0x7594635fcc
	private Void _OnSellClicked() { }
	// RVA: 0x201e22c VA: 0x759463622c
	private Void _OnUpgradeClicked() { }
	// RVA: 0x201e394 VA: 0x7594636394
	private Void _OnFreezeOrUnFreezeClicked() { }
	// RVA: 0x201e4d8 VA: 0x75946364d8
	private Void _OnBuyClicked() { }
	// RVA: 0x201e5f0 VA: 0x75946365f0
	private Void _OnRefreshClicked() { }
	// RVA: 0x201e714 VA: 0x7594636714
	private Void _OnWithdrawClicked() { }
	// RVA: 0x201e980 VA: 0x7594636980
	private Void _OnDestroyClicked() { }
	// RVA: 0x201ebcc VA: 0x7594636bcc
	private Boolean _IsUtilTrapValid() { }
	// RVA: 0x201ed1c VA: 0x7594636d1c
	private Boolean _IsUpgradeValid() { }
	// RVA: 0x201edc0 VA: 0x7594636dc0
	private Boolean _IsRefreshValid() { }
	// RVA: 0x201d388 VA: 0x7594635388
	private Boolean _IsBuyValid() { }
	// RVA: 0x201d4c8 VA: 0x75946354c8
	private Boolean _IsSellOrDestoryValid() { }
	// RVA: 0x201e0f0 VA: 0x75946360f0
	private Boolean _CheckUtilFastClicked(String key) { }
	// RVA: 0x201ee64 VA: 0x7594636e64
	public Void .ctor() { }
}
```