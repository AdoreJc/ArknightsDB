# UIBattleLegionRedrawPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Text _curCntText`

- `Text _totalCntText`

- `UIAtlasImage _imgTipBg`

- `Text _remainingCardCountText`

- `Text _usedCardCountText`

- `ThreeStateToggle _redrawBtnToggle`

- `Color _bgCanStart`

- `Color _bgNotStart`

- `Color _numCommon`

- `Color _numBeyond`

- `LegionUICardRedrawState m_legionState`

- `Int32 m_totalCnt`


## Methods

- `Void Show(LegionUICardRedrawState, LegionGameMode)`

- `Void ShowRedrawCards(Int32)`

- `Void OnConfirmClick()`

- `Void OnUnselectClick()`

- `Void OnShowPendingCard()`

- `Void OnShowUsedCard()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleLegionRedrawPanel : MonoBehaviour, IHotfixable
{
	private Text _curCntText; // 0x18
	private Text _totalCntText; // 0x20
	private UIAtlasImage _imgTipBg; // 0x28
	private Text _remainingCardCountText; // 0x30
	private Text _usedCardCountText; // 0x38
	private ThreeStateToggle _redrawBtnToggle; // 0x40
	private Color _bgCanStart; // 0x48
	private Color _bgNotStart; // 0x58
	private Color _numCommon; // 0x68
	private Color _numBeyond; // 0x78
	private LegionUICardRedrawState m_legionState; // 0x88
	private Int32 m_totalCnt; // 0x90
	private const String DEFAULT_CNT; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix0_ShowRedrawCards; // 0x8
	private static DelegateBridge __Hotfix0_OnConfirmClick; // 0x10
	private static DelegateBridge __Hotfix0_OnUnselectClick; // 0x18
	private static DelegateBridge __Hotfix0_OnShowPendingCard; // 0x20
	private static DelegateBridge __Hotfix0_OnShowUsedCard; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x203ebd8 VA: 0x7594656bd8
	public Void Show(LegionUICardRedrawState legionState, LegionGameMode manager) { }
	// RVA: 0x203edd4 VA: 0x7594656dd4
	public Void ShowRedrawCards(Int32 curCnt) { }
	// RVA: 0x203ef78 VA: 0x7594656f78
	public Void OnConfirmClick() { }
	// RVA: 0x203efec VA: 0x7594656fec
	public Void OnUnselectClick() { }
	// RVA: 0x203f060 VA: 0x7594657060
	public Void OnShowPendingCard() { }
	// RVA: 0x203f0d4 VA: 0x75946570d4
	public Void OnShowUsedCard() { }
	// RVA: 0x203f148 VA: 0x7594657148
	public Void .ctor() { }
}
```