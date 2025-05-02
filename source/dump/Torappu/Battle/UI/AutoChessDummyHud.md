# AutoChessDummyHud

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIFollower _follower`

- `Transform _root`

- `Transform _chessLevelRoot`

- `Image _chessLevelImage`

- `CanvasGroup _shopPart`

- `Transform _equipRoot`

- `Image _equip1Icon`

- `Image _equip2Icon`

- `Sprite _goldSprite`

- `Sprite _whiteSprite`

- `Transform _priceRoot`

- `Text _priceText`

- `Transform _tokenRoot`

- `Text _tokenCntText`

- `Transform _upgradeRoot`

- `Text _upgradeText`

- `Color _invalidUpgradeColor`

- `Transform _battleStateRoot`

- `Transform _respawnReadyRoot`

- `Transform _respawnCountdownRoot`

- `Image _respawnCountdownFill`

- `Sprite _coinEnoughSprite`

- `Sprite _coinNotEnoughSprite`

- `Image _coinImg`

- `Color _colorEnough`

- `Color _colorNotEnough`

- `Param m_param`

- `Boolean m_inited`


## Methods

- `Void InitIfNot()`

- `Void SetData(Param)`

- `Void UpdateGameInfo()`

- `Void Hide()`

- `Void _UpdataInternal(Boolean)`

- `Void _UpdateShopState()`

- `Void _UpdateBattleState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class AutoChessDummyHud : BattleReusableUI
{
	private UIFollower _follower; // 0x20
	private Transform _root; // 0x28
	private Transform _chessLevelRoot; // 0x30
	private Image _chessLevelImage; // 0x38
	private Sprite[] _chessLevelSprites; // 0x40
	private CanvasGroup _shopPart; // 0x48
	private Transform _equipRoot; // 0x50
	private Image _equip1Icon; // 0x58
	private Image _equip2Icon; // 0x60
	private Sprite _goldSprite; // 0x68
	private Sprite _whiteSprite; // 0x70
	private Transform _priceRoot; // 0x78
	private Text _priceText; // 0x80
	private Transform _tokenRoot; // 0x88
	private Text _tokenCntText; // 0x90
	private Transform _upgradeRoot; // 0x98
	private Text _upgradeText; // 0xa0
	private Color _invalidUpgradeColor; // 0xa8
	private Transform _battleStateRoot; // 0xb8
	private Transform _respawnReadyRoot; // 0xc0
	private Transform _respawnCountdownRoot; // 0xc8
	private Image _respawnCountdownFill; // 0xd0
	private Sprite _coinEnoughSprite; // 0xd8
	private Sprite _coinNotEnoughSprite; // 0xe0
	private Image _coinImg; // 0xe8
	private Color _colorEnough; // 0xf0
	private Color _colorNotEnough; // 0x100
	private const String TOKEN_CNT_FORMAT; // 0x0
	private Param m_param; // 0x110
	private Boolean m_inited; // 0x160
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x10
	private static DelegateBridge __Hotfix0_Hide; // 0x18
	private static DelegateBridge __Hotfix0__UpdataInternal; // 0x20
	private static DelegateBridge __Hotfix0__UpdateShopState; // 0x28
	private static DelegateBridge __Hotfix0__UpdateBattleState; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x202a0b4 VA: 0x75946420b4
	public Void InitIfNot() { }
	// RVA: 0x202a128 VA: 0x7594642128
	public Void SetData(Param param) { }
	// RVA: 0x202a340 VA: 0x7594642340
	public Void UpdateGameInfo() { }
	// RVA: 0x202a3c0 VA: 0x75946423c0
	public Void Hide() { }
	// RVA: 0x202a1f0 VA: 0x75946421f0
	private Void _UpdataInternal(Boolean needUpdateShopState) { }
	// RVA: 0x202a5ec VA: 0x75946425ec
	private Void _UpdateShopState() { }
	// RVA: 0x202a434 VA: 0x7594642434
	private Void _UpdateBattleState() { }
	// RVA: 0x202aa3c VA: 0x7594642a3c
	public Void .ctor() { }
}
```