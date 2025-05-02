# UICardLegionSelectItem

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `UIAtlasObject _atlas`

- `RectTransform _transDownPart`

- `GameObject _objDownCharPart`

- `UIAtlasImage _imgPortrait`

- `GameObject _imgDiscardDec`

- `GameObject _objDownTrapPart`

- `Image _imgTrap`

- `CanvasGroup _canvasSelect`

- `GameObject _objSelectNum`

- `Text _txtSelectNum`

- `GameObject _objSelectDec`

- `GameObject _objDiscardDec`

- `GameObject _objPurpleDec`

- `CanvasGroup _canvasSelectTips`

- `Text _txtSelectBeyondTips`

- `GameObject _objSelectPendingDec`

- `GameObject _objSelectUsedDec`

- `RectTransform _transInfoPart`

- `GameObject _objCharInfoPart`

- `UIAtlasImage _imgRarity`

- `UIAtlasImage _imgElite`

- `UIAtlasImage _imgProfession`

- `Text _txtCharName`

- `GameObject _objTrapInfoPart`

- `Text _txtTrapName`

- `RectTransform _transClickArea`

- `RectTransform rectTweenRoot`

- `CanvasGroup canvasTweenRoot`

- `CardModel m_itemModel`

- `UInt32 m_cacheCardId`

- `Boolean m_isChar`

- `CardSelectPopTween m_selectTween`

- `Boolean m_isInited`

- `Boolean m_isApplied`


## Methods

- `Void ApplyData(CardModel)`

- `Void OnCardClick()`

- `Void OnDetailClick()`

- `Void _InitOrNot()`

- `Void _SetProfession(ProfessionCategory)`

- `Void _SetRarity(RarityRank)`

- `Void _SetElite(EvolvePhase)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class UICardLegionSelectItem : MonoBehaviour, IHotfixable
{
	private UIAtlasObject _atlas; // 0x18
	private RectTransform _transDownPart; // 0x20
	private GameObject _objDownCharPart; // 0x28
	private UIAtlasImage _imgPortrait; // 0x30
	private GameObject _imgDiscardDec; // 0x38
	private GameObject _objDownTrapPart; // 0x40
	private Image _imgTrap; // 0x48
	private CanvasGroup _canvasSelect; // 0x50
	private GameObject _objSelectNum; // 0x58
	private Text _txtSelectNum; // 0x60
	private GameObject _objSelectDec; // 0x68
	private GameObject _objDiscardDec; // 0x70
	private GameObject _objPurpleDec; // 0x78
	private CanvasGroup _canvasSelectTips; // 0x80
	private Text _txtSelectBeyondTips; // 0x88
	private GameObject _objSelectPendingDec; // 0x90
	private GameObject _objSelectUsedDec; // 0x98
	private RectTransform _transInfoPart; // 0xa0
	private GameObject _objCharInfoPart; // 0xa8
	private UIAtlasImage _imgRarity; // 0xb0
	private UIAtlasImage _imgElite; // 0xb8
	private UIAtlasImage _imgProfession; // 0xc0
	private Text _txtCharName; // 0xc8
	private GameObject _objTrapInfoPart; // 0xd0
	private Text _txtTrapName; // 0xd8
	private RectTransform _transClickArea; // 0xe0
	public RectTransform rectTweenRoot; // 0xe8
	public CanvasGroup canvasTweenRoot; // 0xf0
	private ProfessionSpritePair[] _professionIcons; // 0xf8
	public Action`1 onCardClickEvent; // 0x100
	public Action`2 onShowTrapDetail; // 0x108
	private CardModel m_itemModel; // 0x110
	private UInt32 m_cacheCardId; // 0x118
	private Boolean m_isChar; // 0x11c
	private CardSelectPopTween m_selectTween; // 0x120
	private Boolean m_isInited; // 0x128
	private Boolean m_isApplied; // 0x129
	private const String SELECT_NUM_PREFIX; // 0x0
	private const String ELITY_SPRITE_PREFIX; // 0x0
	private const String RARITY_SPRITE_PREFIX; // 0x0
	private static readonly Vector2 SELECT_CARD_CLICK_AREA_SIZE; // 0x0
	private static readonly Vector2 UNSELECT_CARD_CLICK_AREA_SIZE; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge __Hotfix0_OnCardClick; // 0x18
	private static DelegateBridge __Hotfix0_OnDetailClick; // 0x20
	private static DelegateBridge __Hotfix0__InitOrNot; // 0x28
	private static DelegateBridge __Hotfix0__SetProfession; // 0x30
	private static DelegateBridge __Hotfix0__SetRarity; // 0x38
	private static DelegateBridge __Hotfix0__SetElite; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x1dc0470 VA: 0x75943d8470
	public Void ApplyData(CardModel itemModel) { }
	// RVA: 0x1dc12e0 VA: 0x75943d92e0
	public Void OnCardClick() { }
	// RVA: 0x1dc1378 VA: 0x75943d9378
	public Void OnDetailClick() { }
	// RVA: 0x1dc0b94 VA: 0x75943d8b94
	private Void _InitOrNot() { }
	// RVA: 0x1dc0e80 VA: 0x75943d8e80
	private Void _SetProfession(ProfessionCategory profession) { }
	// RVA: 0x1dc1100 VA: 0x75943d9100
	private Void _SetRarity(RarityRank rarity) { }
	// RVA: 0x1dc0fb8 VA: 0x75943d8fb8
	private Void _SetElite(EvolvePhase elity) { }
	// RVA: 0x1dc158c VA: 0x75943d958c
	public Void .ctor() { }
	// RVA: 0x1dc160c VA: 0x75943d960c
	private static Void .cctor() { }
}
```