# CharacterLvlupItemCollectionView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `SimpleLayoutContent _itemLayoutContent`

- `RectTransform _goldContainer`

- `CharacterLvlupItemCard _cardPrefab`

- `Boolean m_isInited`

- `ItemAdapter m_adapter`

- `CharacterLvlupItemCard m_goldCard`


## Methods

- `Void Render(CharacterLvlupItemCollectionViewModel)`

- `Void _InitIfNot()`

- `Void _OnModifyingCardNum(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupItemCollectionView : MonoBehaviour, IHotfixable
{
	private const Int32 AVG_FOCUS_ITEM_INDEX; // 0x0
	private SimpleLayoutContent _itemLayoutContent; // 0x18
	private RectTransform _goldContainer; // 0x20
	private CharacterLvlupItemCard _cardPrefab; // 0x28
	public Action`2 onModifyingCardNum; // 0x30
	private Boolean m_isInited; // 0x38
	private ItemAdapter m_adapter; // 0x40
	private CharacterLvlupItemCard m_goldCard; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnModifyingCardNum; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d75830 VA: 0x759538d830
	public Void Render(CharacterLvlupItemCollectionViewModel viewModel) { }
	// RVA: 0x2d77c40 VA: 0x759538fc40
	private Void _InitIfNot() { }
	// RVA: 0x2d77d34 VA: 0x759538fd34
	private Void _OnModifyingCardNum(Int32 index, Int32 num) { }
	// RVA: 0x2d77de0 VA: 0x759538fde0
	public Void .ctor() { }
}
```