# CharacterInfoSkillRequireItemView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _contentForItem`

- `Transform _itemCardContainer`

- `GameObject _contentForText`

- `Text _contentTextValue`

- `GameObject _contentForFavor`

- `Text _contentFavorValue`

- `Int32 _textValueUnitSize`

- `Image _contentEvolveState`

- `GameObject _satisfiedLabel`

- `GameObject _unsatisfiedLabel`

- `Text _labelCountDesc`

- `Color _unsatisfiedLabelColor`

- `Int32 _labelLengthLimit`

- `Single _itemCardScale`

- `UIItemCard m_itemCard`

- `Int64 m_cachedNeedCount`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void RenderItem(Int32, RequireViewModel)`

- `Void _RenderFavorItem(RequireViewModel)`

- `Void _OnItemClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSkillRequireItemView : MonoBehaviour, IHotfixable
{
	private GameObject _contentForItem; // 0x18
	private Transform _itemCardContainer; // 0x20
	private GameObject _contentForText; // 0x28
	private Text _contentTextValue; // 0x30
	private GameObject _contentForFavor; // 0x38
	private Text _contentFavorValue; // 0x40
	private Int32 _textValueUnitSize; // 0x48
	private Image _contentEvolveState; // 0x50
	private GameObject _satisfiedLabel; // 0x58
	private GameObject _unsatisfiedLabel; // 0x60
	private Text _labelCountDesc; // 0x68
	private Color _unsatisfiedLabelColor; // 0x70
	private Int32 _labelLengthLimit; // 0x80
	private Single _itemCardScale; // 0x84
	private UIItemCard m_itemCard; // 0x88
	private Int64 m_cachedNeedCount; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderItem; // 0x8
	private static DelegateBridge __Hotfix0__RenderFavorItem; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d89f84 VA: 0x75953a1f84
	private Void _InitIfNot() { }
	// RVA: 0x2d8a198 VA: 0x75953a2198
	public Void RenderItem(Int32 index, RequireViewModel viewModel) { }
	// RVA: 0x2d8a5ac VA: 0x75953a25ac
	private Void _RenderFavorItem(RequireViewModel viewModel) { }
	// RVA: 0x2d8a680 VA: 0x75953a2680
	private Void _OnItemClicked(Int32 index) { }
	// RVA: 0x2d8a788 VA: 0x75953a2788
	public Void .ctor() { }
}
```