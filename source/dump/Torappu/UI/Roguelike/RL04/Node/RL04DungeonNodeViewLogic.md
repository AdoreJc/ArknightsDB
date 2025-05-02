# RL04DungeonNodeViewLogic

**Namespace:** `Torappu.UI.Roguelike.RL04.Node`


## Fields

- `Image _unactiveImg`

- `GameObject _mask`

- `GameObject _bossEffect`

- `GameObject _finalBossEffect`

- `GameObject _panelNodeUpgrade`

- `GameObject _lvluped`

- `GameObject _ableToLvlup`

- `GameObject _lvlupedHotspot`

- `RoguelikeDetailNodeDialog _detailDialogPrefab`

- `GameObject _normalGroupObj`

- `Text _verCountNum`

- `GameObject _amiyaBlurObj`

- `Color _amiyaWidgetColor`

- `Color _amiyaReflectColor`


## Properties

- `Boolean m_isAmiyaSpecialNode`


## Methods

- `Boolean get_m_isAmiyaSpecialNode()`

- `Void _RenderNodeUpdate()`

- `Void _RenderAmiyaZoneNode()`

- `Void OnLvlupedClick()`

- `Void <>xLuaBaseProxy_RenderBossWidgets()`

- `Void <>xLuaBaseProxy_RenderNonBossWidigets()`

- `Void <>xLuaBaseProxy_RenderOtherWidgets()`

- `Void <>xLuaBaseProxy_RenderCurves()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04.Node
public class RL04DungeonNodeViewLogic : RoguelikeDungeonNodeDefaultLogic
{
	private Image _unactiveImg; // 0x20
	private GameObject _mask; // 0x28
	private GameObject _bossEffect; // 0x30
	private GameObject _finalBossEffect; // 0x38
	private GameObject _panelNodeUpgrade; // 0x40
	private GameObject _lvluped; // 0x48
	private GameObject _ableToLvlup; // 0x50
	private GameObject _lvlupedHotspot; // 0x58
	private RoguelikeDetailNodeDialog _detailDialogPrefab; // 0x60
	private GameObject _normalGroupObj; // 0x68
	private Text _verCountNum; // 0x70
	private GameObject _amiyaBlurObj; // 0x78
	private Color _amiyaWidgetColor; // 0x80
	private Color _amiyaReflectColor; // 0x90
	private static DelegateBridge __Hotfix0_get_m_isAmiyaSpecialNode; // 0x0
	private static DelegateBridge __Hotfix0_RenderBossWidgets; // 0x8
	private static DelegateBridge __Hotfix0_RenderNonBossWidigets; // 0x10
	private static DelegateBridge __Hotfix0_RenderOtherWidgets; // 0x18
	private static DelegateBridge __Hotfix0_RenderCurves; // 0x20
	private static DelegateBridge __Hotfix0__RenderNodeUpdate; // 0x28
	private static DelegateBridge __Hotfix0__RenderAmiyaZoneNode; // 0x30
	private static DelegateBridge __Hotfix0_OnLvlupedClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean m_isAmiyaSpecialNode { get; }

	// RVA: 0x2b577a4 VA: 0x759516f7a4
	private Boolean get_m_isAmiyaSpecialNode() { }
	// RVA: 0x2b57858 VA: 0x759516f858
	public override Void RenderBossWidgets() { }
	// RVA: 0x2b57dbc VA: 0x759516fdbc
	public override Void RenderNonBossWidigets() { }
	// RVA: 0x2b58920 VA: 0x7595170920
	public override Void RenderOtherWidgets() { }
	// RVA: 0x2b58c38 VA: 0x7595170c38
	public override Void RenderCurves() { }
	// RVA: 0x2b589ec VA: 0x75951709ec
	private Void _RenderNodeUpdate() { }
	// RVA: 0x2b57cd8 VA: 0x759516fcd8
	private Void _RenderAmiyaZoneNode() { }
	// RVA: 0x2b59c38 VA: 0x7595171c38
	public Void OnLvlupedClick() { }
	// RVA: 0x2b5a040 VA: 0x7595172040
	public Void .ctor() { }
	// RVA: 0x2b5a0c4 VA: 0x75951720c4
	private Void <>xLuaBaseProxy_RenderBossWidgets() { }
	// RVA: 0x2b5a0cc VA: 0x75951720cc
	private Void <>xLuaBaseProxy_RenderNonBossWidigets() { }
	// RVA: 0x2b5a0d4 VA: 0x75951720d4
	private Void <>xLuaBaseProxy_RenderOtherWidgets() { }
	// RVA: 0x2b5a0dc VA: 0x75951720dc
	private Void <>xLuaBaseProxy_RenderCurves() { }
}
```