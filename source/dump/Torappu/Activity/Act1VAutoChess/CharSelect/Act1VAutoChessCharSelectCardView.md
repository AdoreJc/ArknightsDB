# Act1VAutoChessCharSelectCardView

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `Act1VAutoChessShopCharChessCardView _cardPrefab`

- `Transform _cardContainer`

- `Text _selectedIndex`

- `Act1VAutoChessShopCharChessCardView m_chessCard`


## Methods

- `Void _InitIfNot()`

- `Void _EventOnChessCardClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectCardView : TemplateCharSelectCardView
{
	private Act1VAutoChessShopCharChessCardView _cardPrefab; // 0x38
	private Transform _cardContainer; // 0x40
	private Text _selectedIndex; // 0x48
	private Act1VAutoChessShopCharChessCardView m_chessCard; // 0x50
	private static DelegateBridge __Hotfix0_DoRender; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__EventOnChessCardClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3384d94 VA: 0x759599cd94
	protected override Void DoRender(TemplateCharSelectCardViewModel viewModel) { }
	// RVA: 0x3384ecc VA: 0x759599cecc
	private Void _InitIfNot() { }
	// RVA: 0x3385040 VA: 0x759599d040
	private Void _EventOnChessCardClick(String chessId) { }
	// RVA: 0x33850c0 VA: 0x759599d0c0
	public Void .ctor() { }
}
```