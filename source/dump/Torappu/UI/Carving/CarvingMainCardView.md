# CarvingMainCardView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `UIAtlasObject _atlasObject`

- `UIAtlasImage _cardLevel`

- `UIAtlasImage _cardBgType`

- `GameObject _cardUpgradeIcon`

- `UIAnimationLocation _selectHandAnimLocation`

- `UIAnimationLocation _selectShopAnimLocation`

- `UIAnimationLocation _selectSlotAnimLocation`

- `UIAnimationLocation _selectLightAnimLocation`

- `UIAnimationLocation _selectedInShopAnimLocation`

- `UIAnimationLocation _selectedAsTokenAnimLocation`

- `CanvasGroup _selectedInShopAlphaHandler`

- `UIAnimationLocation _levelUpAnimLocation`

- `UIAnimationLocation _processedAnimLocation`

- `UIColorGraphic _cardGraphic`

- `UIScaler _uiScaler`

- `Boolean m_inited`

- `UISwitchTween m_selectAnimSwitchTween`

- `UISwitchTween m_selectedInShopSwitchTween`

- `Tween m_selectLightTween`

- `Tween m_levelUpTween`

- `Tween m_processedTween`

- `Boolean m_cachedSelect`

- `Boolean m_cachedSelectedInShop`

- `Int32 m_cachedCardLevel`

- `ShowType m_cachedShowType`


## Properties

- `UIColorGraphic cardGraphic`


## Methods

- `UIColorGraphic get_cardGraphic()`

- `Void _InitIfNot(ShowType)`

- `Void Render(CarvingMainCardViewModel, RenderParam)`

- `Single GetScaler()`

- `Void SetScaler(Single)`

- `Void _RenderSelection(Boolean, Boolean)`

- `Void _RenderSelectionInShop(Boolean, Boolean)`

- `Void _PlayProcessed(Boolean)`

- `Void _PlaySelectLightTween()`

- `Void _RenderLevelUp(CarvingMainCardViewModel)`

- `Void _RenderCardContent(CarvingMainCardViewModel)`

- `Void _RenderTargetTransfer(List`1, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainCardView : MonoBehaviour, IHotfixable
{
	private const String CARD_LEVEL_IMG; // 0x0
	private UIAtlasObject _atlasObject; // 0x18
	private UIAtlasImage _cardLevel; // 0x20
	private UIAtlasImage _cardBgType; // 0x28
	private GameObject _cardUpgradeIcon; // 0x30
	private List`1 _cardTransfers; // 0x38
	private UIAnimationLocation _selectHandAnimLocation; // 0x40
	private UIAnimationLocation _selectShopAnimLocation; // 0x50
	private UIAnimationLocation _selectSlotAnimLocation; // 0x60
	private UIAnimationLocation _selectLightAnimLocation; // 0x70
	private UIAnimationLocation _selectedInShopAnimLocation; // 0x80
	private UIAnimationLocation _selectedAsTokenAnimLocation; // 0x90
	private CanvasGroup _selectedInShopAlphaHandler; // 0xa0
	private UIAnimationLocation _levelUpAnimLocation; // 0xa8
	private UIAnimationLocation _processedAnimLocation; // 0xb8
	private UIColorGraphic _cardGraphic; // 0xc8
	private UIScaler _uiScaler; // 0xd0
	private Boolean m_inited; // 0xd8
	private UISwitchTween m_selectAnimSwitchTween; // 0xe0
	private UISwitchTween m_selectedInShopSwitchTween; // 0xe8
	private Tween m_selectLightTween; // 0xf0
	private Tween m_levelUpTween; // 0xf8
	private Tween m_processedTween; // 0x100
	private Boolean m_cachedSelect; // 0x108
	private Boolean m_cachedSelectedInShop; // 0x109
	private Int32 m_cachedCardLevel; // 0x10c
	private ShowType m_cachedShowType; // 0x110
	private static DelegateBridge __Hotfix0_get_cardGraphic; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_GetScaler; // 0x18
	private static DelegateBridge __Hotfix0_SetScaler; // 0x20
	private static DelegateBridge __Hotfix0__RenderSelection; // 0x28
	private static DelegateBridge __Hotfix0__RenderSelectionInShop; // 0x30
	private static DelegateBridge __Hotfix0__PlayProcessed; // 0x38
	private static DelegateBridge __Hotfix0__PlaySelectLightTween; // 0x40
	private static DelegateBridge __Hotfix0__RenderLevelUp; // 0x48
	private static DelegateBridge __Hotfix0__RenderCardContent; // 0x50
	private static DelegateBridge __Hotfix0__RenderTargetTransfer; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public UIColorGraphic cardGraphic { get; }

	// RVA: 0x2da6a84 VA: 0x75953bea84
	public UIColorGraphic get_cardGraphic() { }
	// RVA: 0x2da6aec VA: 0x75953beaec
	private Void _InitIfNot(ShowType showType) { }
	// RVA: 0x2da6d60 VA: 0x75953bed60
	public Void Render(CarvingMainCardViewModel model, RenderParam renderParam) { }
	// RVA: 0x2da7480 VA: 0x75953bf480
	public Single GetScaler() { }
	// RVA: 0x2da7538 VA: 0x75953bf538
	public Void SetScaler(Single scale) { }
	// RVA: 0x2da6e5c VA: 0x75953bee5c
	private Void _RenderSelection(Boolean isSelect, Boolean isFastMode) { }
	// RVA: 0x2da6f40 VA: 0x75953bef40
	private Void _RenderSelectionInShop(Boolean isSelectedInShop, Boolean isFastMode) { }
	// RVA: 0x2da7010 VA: 0x75953bf010
	private Void _PlayProcessed(Boolean isProcessed) { }
	// RVA: 0x2da7610 VA: 0x75953bf610
	private Void _PlaySelectLightTween() { }
	// RVA: 0x2da7144 VA: 0x75953bf144
	private Void _RenderLevelUp(CarvingMainCardViewModel model) { }
	// RVA: 0x2da72b8 VA: 0x75953bf2b8
	private Void _RenderCardContent(CarvingMainCardViewModel model) { }
	// RVA: 0x2da7880 VA: 0x75953bf880
	private Void _RenderTargetTransfer(List`1 inputMaterials, List`1 outputMaterials) { }
	// RVA: 0x2da79dc VA: 0x75953bf9dc
	public Void .ctor() { }
}
```