# Act1VAutoChessChessShopLevelCharItemCardView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `RectTransform _rectCharViewContainer`

- `RectTransform _rectDiyViewContainer`

- `Act1VAutoChessShopCharChessCardView _chessCardViewPrefab`

- `Act1VAutoChessShopCharChessDiyCardView _chessDiyCardViewPrefab`

- `RectTransform _rectSkillAndModuleEditContainer`

- `Act1VAutoChessChessShopLevelSkillAndModuleEditItemView _skillAndModuleEditItemViewPrefab`

- `Transform _trackPointContainer`

- `GameObject _objNewPrefab`

- `UIStateFinder m_stateFinder`

- `Act1VAutoChessShopCharChessCardView m_charChessCardView`

- `Act1VAutoChessShopCharChessDiyCardView m_diyCardView`

- `Act1VAutoChessChessShopLevelSkillAndModuleEditItemView m_skillAndModuleEditItemView`

- `String m_cachedChessId`

- `Int32 m_cachedChessLv`

- `GameObject m_trackPointObj`

- `IDragHandler <parentScrollHandler>k__BackingField`


## Properties

- `IDragHandler parentScrollHandler`

- `GameObject objLeftInfoPart`


## Methods

- `IDragHandler get_parentScrollHandler()`

- `Void set_parentScrollHandler(IDragHandler)`

- `GameObject get_objLeftInfoPart()`

- `Void Render(Act1VAutoChessChessShopLevelCharItemCardViewModel)`

- `ValueBundle _GenClickParams()`

- `Void _SetCharNewTrackPoint(Boolean)`

- `Void _OnCharDiyItemClick(String)`

- `Void _OnCharItemClick(String)`

- `Void _OnCharCancelClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopLevelCharItemCardView : MonoBehaviour, IHotfixable
{
	private RectTransform _rectCharViewContainer; // 0x18
	private RectTransform _rectDiyViewContainer; // 0x20
	private Act1VAutoChessShopCharChessCardView _chessCardViewPrefab; // 0x28
	private Act1VAutoChessShopCharChessDiyCardView _chessDiyCardViewPrefab; // 0x30
	private RectTransform _rectSkillAndModuleEditContainer; // 0x38
	private Act1VAutoChessChessShopLevelSkillAndModuleEditItemView _skillAndModuleEditItemViewPrefab; // 0x40
	private Transform _trackPointContainer; // 0x48
	private GameObject _objNewPrefab; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private Act1VAutoChessShopCharChessCardView m_charChessCardView; // 0x68
	private Act1VAutoChessShopCharChessDiyCardView m_diyCardView; // 0x70
	private Act1VAutoChessChessShopLevelSkillAndModuleEditItemView m_skillAndModuleEditItemView; // 0x78
	private String m_cachedChessId; // 0x80
	private Int32 m_cachedChessLv; // 0x88
	private GameObject m_trackPointObj; // 0x90
	private IDragHandler <parentScrollHandler>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_parentScrollHandler; // 0x0
	private static DelegateBridge __Hotfix0_set_parentScrollHandler; // 0x8
	private static DelegateBridge __Hotfix0_get_objLeftInfoPart; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__GenClickParams; // 0x20
	private static DelegateBridge __Hotfix0__SetCharNewTrackPoint; // 0x28
	private static DelegateBridge __Hotfix0__OnCharDiyItemClick; // 0x30
	private static DelegateBridge __Hotfix0__OnCharItemClick; // 0x38
	private static DelegateBridge __Hotfix0__OnCharCancelClick; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public IDragHandler parentScrollHandler { get; set; }
	public GameObject objLeftInfoPart { get; }

	// RVA: 0x331c8cc VA: 0x75959348cc
	public IDragHandler get_parentScrollHandler() { }
	// RVA: 0x331c258 VA: 0x7595934258
	public Void set_parentScrollHandler(IDragHandler value) { }
	// RVA: 0x331c934 VA: 0x7595934934
	public GameObject get_objLeftInfoPart() { }
	// RVA: 0x331c2dc VA: 0x75959342dc
	public Void Render(Act1VAutoChessChessShopLevelCharItemCardViewModel itemCardViewModel) { }
	// RVA: 0x331d3d8 VA: 0x75959353d8
	private ValueBundle _GenClickParams() { }
	// RVA: 0x331ce78 VA: 0x7595934e78
	private Void _SetCharNewTrackPoint(Boolean isShow) { }
	// RVA: 0x331d488 VA: 0x7595935488
	private Void _OnCharDiyItemClick(String chessId) { }
	// RVA: 0x331d554 VA: 0x7595935554
	private Void _OnCharItemClick(String chessId) { }
	// RVA: 0x331d620 VA: 0x7595935620
	private Void _OnCharCancelClick(String chessId) { }
	// RVA: 0x331d720 VA: 0x7595935720
	public Void .ctor() { }
}
```