# GrocerySellResultRankItem

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Image _shopIconPlayer`

- `Image _shopIconNpc`

- `Text _sellPriceText`

- `Text _sellNumText`

- `Text _sellIncomeText`

- `Text _prizeIncomeText`

- `Text _rankText`

- `UIAtlasImage _sellIncomeBkg`

- `UIAtlasImage _prizeIcon`

- `GameObject _playerSoldOutObject`

- `TwoStateToggle _shopIconToggle`

- `TwoStateToggle _priceTextToggle`

- `TwoStateToggle _sellTextToggle`

- `TwoStateToggle _incomeTextToggle`

- `TwoStateToggle _prizeTextToggle`

- `TwoStateToggle _rankIconToggle`

- `AnimationWrapper _animationWrapper`

- `UIStateFinder m_stateFinder`

- `Tween m_tween`

- `Int32 m_cachedRank`


## Properties

- `Int32 cachedRank`


## Methods

- `Int32 get_cachedRank()`

- `Void Render(SellInfo, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultRankItem : MonoBehaviour, IHotfixable
{
	private const String PLAYER_SHOP_ICON_ANIM; // 0x0
	private static readonly Color PLAYER_COLOR; // 0x0
	private static readonly Color NPC_COLOR; // 0x10
	private Image _shopIconPlayer; // 0x18
	private Image _shopIconNpc; // 0x20
	private Text _sellPriceText; // 0x28
	private Text _sellNumText; // 0x30
	private Text _sellIncomeText; // 0x38
	private Text _prizeIncomeText; // 0x40
	private Text _rankText; // 0x48
	private UIAtlasImage _sellIncomeBkg; // 0x50
	private UIAtlasImage _prizeIcon; // 0x58
	private GameObject _playerSoldOutObject; // 0x60
	private TwoStateToggle _shopIconToggle; // 0x68
	private TwoStateToggle _priceTextToggle; // 0x70
	private TwoStateToggle _sellTextToggle; // 0x78
	private TwoStateToggle _incomeTextToggle; // 0x80
	private TwoStateToggle _prizeTextToggle; // 0x88
	private TwoStateToggle _rankIconToggle; // 0x90
	private AnimationWrapper _animationWrapper; // 0x98
	private UIStateFinder m_stateFinder; // 0xa0
	private Tween m_tween; // 0xb0
	private Int32 m_cachedRank; // 0xb8
	private static DelegateBridge __Hotfix0_get_cachedRank; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 cachedRank { get; }

	// RVA: 0x28a31e8 VA: 0x7594ebb1e8
	public Int32 get_cachedRank() { }
	// RVA: 0x28a3260 VA: 0x7594ebb260
	public Void Render(SellInfo model, Int32 rank) { }
	// RVA: 0x28a38c4 VA: 0x7594ebb8c4
	public Void .ctor() { }
	// RVA: 0x28a3944 VA: 0x7594ebb944
	private static Void .cctor() { }
}
```