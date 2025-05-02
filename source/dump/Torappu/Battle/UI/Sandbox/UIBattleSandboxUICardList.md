# UIBattleSandboxUICardList

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `GameObject _normalModePart`

- `GameObject _buildModePart`

- `Text _textCurPage`

- `Text _textTotalPage`

- `Int32 _cardListMaxCnt`

- `Button _buttonToggle`

- `Transform _topLine`

- `GameObject _viewPrefab`

- `UIBattleSandboxDeco _deco`

- `SandboxGameMode m_gameMode`

- `UIController m_uiCtrl`

- `Int32 m_curPage`

- `Int32 m_totalPage`

- `Int32 m_cachedcurPage`

- `Int32 m_cachedTotalPage`


## Properties

- `Int32 cardListMaxCnt`

- `SandboxGameMode sandboxGameMode`


## Methods

- `Int32 get_cardListMaxCnt()`

- `SandboxGameMode get_sandboxGameMode()`

- `Void Update()`

- `Void OnInit(SandboxUIPlugin, UIController)`

- `Void UpdateGameInfo()`

- `Void _UpdateInfo()`

- `Void _UpdateTopLine()`

- `Void OnTurnPageClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxUICardList : MonoBehaviour, IHotfixable
{
	private GameObject _normalModePart; // 0x18
	private GameObject _buildModePart; // 0x20
	private Text _textCurPage; // 0x28
	private Text _textTotalPage; // 0x30
	private Int32 _cardListMaxCnt; // 0x38
	private Button _buttonToggle; // 0x40
	private Transform _topLine; // 0x48
	private GameObject _viewPrefab; // 0x50
	private UIBattleSandboxDeco _deco; // 0x58
	private SandboxGameMode m_gameMode; // 0x60
	private List`1 m_listViews; // 0x68
	private UIController m_uiCtrl; // 0x70
	private Int32 m_curPage; // 0x78
	private Int32 m_totalPage; // 0x7c
	private Int32 m_cachedcurPage; // 0x80
	private Int32 m_cachedTotalPage; // 0x84
	private static readonly Vector2 CardListOffsetMax; // 0x0
	private static readonly Vector2 CardListOffsetMin; // 0x8
	private static DelegateBridge __Hotfix0_get_cardListMaxCnt; // 0x10
	private static DelegateBridge __Hotfix0_get_sandboxGameMode; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x30
	private static DelegateBridge __Hotfix0__UpdateInfo; // 0x38
	private static DelegateBridge __Hotfix0__UpdateTopLine; // 0x40
	private static DelegateBridge __Hotfix0_OnTurnPageClick; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 cardListMaxCnt { get; }
	private SandboxGameMode sandboxGameMode { get; }

	// RVA: 0x20c3abc VA: 0x75946dbabc
	public Int32 get_cardListMaxCnt() { }
	// RVA: 0x20c3b34 VA: 0x75946dbb34
	private SandboxGameMode get_sandboxGameMode() { }
	// RVA: 0x20c3bf4 VA: 0x75946dbbf4
	private Void Update() { }
	// RVA: 0x20c3cb8 VA: 0x75946dbcb8
	public Void OnInit(SandboxUIPlugin sandbox, UIController uiCtrl) { }
	// RVA: 0x20c4038 VA: 0x75946dc038
	public Void UpdateGameInfo() { }
	// RVA: 0x20c3e9c VA: 0x75946dbe9c
	private Void _UpdateInfo() { }
	// RVA: 0x20c40b0 VA: 0x75946dc0b0
	private Void _UpdateTopLine() { }
	// RVA: 0x20c44cc VA: 0x75946dc4cc
	public Void OnTurnPageClick() { }
	// RVA: 0x20c45f8 VA: 0x75946dc5f8
	public Void .ctor() { }
	// RVA: 0x20c46e8 VA: 0x75946dc6e8
	private static Void .cctor() { }
}
```