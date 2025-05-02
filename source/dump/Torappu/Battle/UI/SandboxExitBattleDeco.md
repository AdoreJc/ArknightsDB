# SandboxExitBattleDeco

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Transform _root`

- `Image _iconImage`

- `Text _rushText`

- `Text _rushRatioText`

- `Text _stageText`

- `Text _hintLabel`

- `Transform _lifeRatioRoot`

- `Transform _lifeRatioHomeRoot`

- `Transform _fillImageRoot`

- `Image _fillImage`

- `Text _lifeRatioText`

- `Text _lifeRatioTextHome`

- `Color _homeColorYellow`

- `Color _bossColorRed`

- `Color _defaultColorWhite`


## Properties

- `SandboxGameMode gamemode`

- `SandboxV2NodeType nodeType`


## Methods

- `SandboxGameMode get_gamemode()`

- `SandboxV2NodeType get_nodeType()`

- `Void Awake()`

- `Void _DoRender()`

- `Void _InitDefault()`

- `Void _SetUIVisible()`

- `Void _ShowHome()`

- `Void _ShowMine()`

- `Void _ShowGate()`

- `Void _ShowNest()`

- `Void _ShowCave()`

- `Void _ShowRushOrBattle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class SandboxExitBattleDeco : SandboxV2ConfirmDialogDecoViewBase
{
	private Transform _root; // 0x18
	private Image _iconImage; // 0x20
	private Text _rushText; // 0x28
	private Text _rushRatioText; // 0x30
	private Text _stageText; // 0x38
	private Text _hintLabel; // 0x40
	private Transform _lifeRatioRoot; // 0x48
	private Transform _lifeRatioHomeRoot; // 0x50
	private Transform _fillImageRoot; // 0x58
	private Image _fillImage; // 0x60
	private Text _lifeRatioText; // 0x68
	private Text _lifeRatioTextHome; // 0x70
	private Color _homeColorYellow; // 0x78
	private Color _bossColorRed; // 0x88
	private Color _defaultColorWhite; // 0x98
	private List`1 _nodeTypeIconRef; // 0xa8
	private const String RUSH_RATIO_FORMAT; // 0x0
	private const String LIFE_RATIO_FORMAT; // 0x0
	private static DelegateBridge __Hotfix0_get_gamemode; // 0x0
	private static DelegateBridge __Hotfix0_get_nodeType; // 0x8
	private static DelegateBridge __Hotfix0_Awake; // 0x10
	private static DelegateBridge __Hotfix0__DoRender; // 0x18
	private static DelegateBridge __Hotfix0__InitDefault; // 0x20
	private static DelegateBridge __Hotfix0__SetUIVisible; // 0x28
	private static DelegateBridge __Hotfix0__ShowHome; // 0x30
	private static DelegateBridge __Hotfix0__ShowMine; // 0x38
	private static DelegateBridge __Hotfix0__ShowGate; // 0x40
	private static DelegateBridge __Hotfix0__ShowNest; // 0x48
	private static DelegateBridge __Hotfix0__ShowCave; // 0x50
	private static DelegateBridge __Hotfix0__ShowRushOrBattle; // 0x58
	private static DelegateBridge __Hotfix0_RenderDecoView; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	private SandboxGameMode gamemode { get; }
	private SandboxV2NodeType nodeType { get; }

	// RVA: 0x2052290 VA: 0x759466a290
	private SandboxGameMode get_gamemode() { }
	// RVA: 0x205231c VA: 0x759466a31c
	private SandboxV2NodeType get_nodeType() { }
	// RVA: 0x2052394 VA: 0x759466a394
	private Void Awake() { }
	// RVA: 0x20524d4 VA: 0x759466a4d4
	public Void _DoRender() { }
	// RVA: 0x20523fc VA: 0x759466a3fc
	private Void _InitDefault() { }
	// RVA: 0x20533bc VA: 0x759466b3bc
	private Void _SetUIVisible() { }
	// RVA: 0x2052614 VA: 0x759466a614
	private Void _ShowHome() { }
	// RVA: 0x2052d18 VA: 0x759466ad18
	private Void _ShowMine() { }
	// RVA: 0x2052f4c VA: 0x759466af4c
	private Void _ShowGate() { }
	// RVA: 0x205288c VA: 0x759466a88c
	private Void _ShowNest() { }
	// RVA: 0x2052ae4 VA: 0x759466aae4
	private Void _ShowCave() { }
	// RVA: 0x2053180 VA: 0x759466b180
	private Void _ShowRushOrBattle() { }
	// RVA: 0x2053814 VA: 0x759466b814
	public override Void RenderDecoView(Object param) { }
	// RVA: 0x2053890 VA: 0x759466b890
	public Void .ctor() { }
}
```