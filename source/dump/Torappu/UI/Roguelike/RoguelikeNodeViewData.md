# RoguelikeNodeViewData

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Color _inactiveColor`

- `Color _activeColor`

- `Color _discardedColor`

- `Color _discardedLineColor`

- `Color _discardedVertLineColor`

- `Color _discardedReflectLineColor`

- `Color _discardedReflectArrowColor`

- `Color _discardedBkgColor`

- `Color _discardedIconColor`

- `Color _traceColor`

- `Color _traceBkgColor`

- `Color _traceIconColor`

- `Color _traceDefaultColor`

- `Color _vertLineDefaultColor`

- `Sprite _bossIcon`

- `Sprite _finalBossIcon`

- `Sprite _lineImg`

- `Sprite _lineLockedImg`

- `Sprite _lineHiddenImg`

- `Sprite _hideBattleImg`

- `Sprite _hideEventImg`

- `Color _hideBattleColor`

- `Color _hideEventColor`

- `Color _hideBarBattleColor`

- `Color _hideBarEventColor`

- `GameObject _hideBarBattleEffect`

- `GameObject _hideBarEventEffect`

- `Boolean _useUnActiveSpriteDataFlag`

- `UnActiveNodeData _unactiveSpriteData`

- `UnActiveNodeData _backImgData`

- `Color _finalBossColor`

- `GameObject _finalBossEffect`

- `Color _selectedTextColor`

- `Color _unSelectedTextColor`


## Properties

- `Color inactiveColor`

- `Color activeColor`

- `Color discardedColor`

- `Color discardedLineColor`

- `Color discardedVertLineColor`

- `Color discardedReflectLineColor`

- `Color discardedReflectArrowColor`

- `Color discardedBkgColor`

- `Color discardedIconColor`

- `Color traceColor`

- `Color traceBkgColor`

- `Color traceIconColor`

- `Color traceDefaultColor`

- `Sprite bossIcon`

- `Sprite finalBossIcon`

- `Sprite lineImg`

- `Sprite lineHiddenImg`

- `Sprite lineLockedImg`

- `Color vertLineDefaultColor`

- `Color hideBattleColor`

- `Color hideEventColor`

- `Color hideBarBattleColor`

- `Color hideBarEventColor`

- `Color selectedTextColor`

- `Color unSelectedTextColor`


## Methods

- `Boolean ShouldSerializeunactiveSpriteData()`

- `Color get_inactiveColor()`

- `Color get_activeColor()`

- `Color get_discardedColor()`

- `Color get_discardedLineColor()`

- `Color get_discardedVertLineColor()`

- `Color get_discardedReflectLineColor()`

- `Color get_discardedReflectArrowColor()`

- `Color get_discardedBkgColor()`

- `Color get_discardedIconColor()`

- `Color get_traceColor()`

- `Color get_traceBkgColor()`

- `Color get_traceIconColor()`

- `Color get_traceDefaultColor()`

- `Sprite get_bossIcon()`

- `Sprite get_finalBossIcon()`

- `Sprite get_lineImg()`

- `Sprite get_lineHiddenImg()`

- `Sprite get_lineLockedImg()`

- `Color get_vertLineDefaultColor()`

- `Color get_hideBattleColor()`

- `Color get_hideEventColor()`

- `Color get_hideBarBattleColor()`

- `Color get_hideBarEventColor()`

- `Color get_selectedTextColor()`

- `Color get_unSelectedTextColor()`

- `Color GetSelectableColor(RoguelikeEventType, Boolean, PlayerNodeForesightType, Boolean)`

- `Color GetBottomBarColor(RoguelikeEventType, Boolean, PlayerNodeForesightType, Boolean)`

- `Sprite GetIcon(RoguelikeEventType, PlayerNodeForesightType, Boolean)`

- `Sprite GetUnactiveIcon(RoguelikeEventType)`

- `Sprite GetBackIcon(RoguelikeEventType)`

- `Sprite GetNameIcon(RoguelikeEventType, PlayerNodeForesightType, Boolean)`

- `GameObject GetParticlePrefab(RoguelikeEventType, Boolean, PlayerNodeForesightType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeNodeViewData : ScriptableObject, IHotfixable
{
	private Color _inactiveColor; // 0x18
	private Color _activeColor; // 0x28
	private Color _discardedColor; // 0x38
	private Color _discardedLineColor; // 0x48
	private Color _discardedVertLineColor; // 0x58
	private Color _discardedReflectLineColor; // 0x68
	private Color _discardedReflectArrowColor; // 0x78
	private Color _discardedBkgColor; // 0x88
	private Color _discardedIconColor; // 0x98
	private Color _traceColor; // 0xa8
	private Color _traceBkgColor; // 0xb8
	private Color _traceIconColor; // 0xc8
	private Color _traceDefaultColor; // 0xd8
	private Color _vertLineDefaultColor; // 0xe8
	private List`1 _selectableColors; // 0xf8
	private List`1 _bottomBarColors; // 0x100
	private List`1 _activeIcons; // 0x108
	private List`1 _nameIcons; // 0x110
	private List`1 _particles; // 0x118
	private Sprite _bossIcon; // 0x120
	private Sprite _finalBossIcon; // 0x128
	private Sprite _lineImg; // 0x130
	private Sprite _lineLockedImg; // 0x138
	private Sprite _lineHiddenImg; // 0x140
	private Sprite _hideBattleImg; // 0x148
	private Sprite _hideEventImg; // 0x150
	private Color _hideBattleColor; // 0x158
	private Color _hideEventColor; // 0x168
	private Color _hideBarBattleColor; // 0x178
	private Color _hideBarEventColor; // 0x188
	private GameObject _hideBarBattleEffect; // 0x198
	private GameObject _hideBarEventEffect; // 0x1a0
	private Boolean _useUnActiveSpriteDataFlag; // 0x1a8
	private UnActiveNodeData _unactiveSpriteData; // 0x1b0
	private UnActiveNodeData _backImgData; // 0x1b8
	private Color _finalBossColor; // 0x1c0
	private GameObject _finalBossEffect; // 0x1d0
	private Color _selectedTextColor; // 0x1d8
	private Color _unSelectedTextColor; // 0x1e8
	private static DelegateBridge __Hotfix0_ShouldSerializeunactiveSpriteData; // 0x0
	private static DelegateBridge __Hotfix0_get_inactiveColor; // 0x8
	private static DelegateBridge __Hotfix0_get_activeColor; // 0x10
	private static DelegateBridge __Hotfix0_get_discardedColor; // 0x18
	private static DelegateBridge __Hotfix0_get_discardedLineColor; // 0x20
	private static DelegateBridge __Hotfix0_get_discardedVertLineColor; // 0x28
	private static DelegateBridge __Hotfix0_get_discardedReflectLineColor; // 0x30
	private static DelegateBridge __Hotfix0_get_discardedReflectArrowColor; // 0x38
	private static DelegateBridge __Hotfix0_get_discardedBkgColor; // 0x40
	private static DelegateBridge __Hotfix0_get_discardedIconColor; // 0x48
	private static DelegateBridge __Hotfix0_get_traceColor; // 0x50
	private static DelegateBridge __Hotfix0_get_traceBkgColor; // 0x58
	private static DelegateBridge __Hotfix0_get_traceIconColor; // 0x60
	private static DelegateBridge __Hotfix0_get_traceDefaultColor; // 0x68
	private static DelegateBridge __Hotfix0_get_bossIcon; // 0x70
	private static DelegateBridge __Hotfix0_get_finalBossIcon; // 0x78
	private static DelegateBridge __Hotfix0_get_lineImg; // 0x80
	private static DelegateBridge __Hotfix0_get_lineHiddenImg; // 0x88
	private static DelegateBridge __Hotfix0_get_lineLockedImg; // 0x90
	private static DelegateBridge __Hotfix0_get_vertLineDefaultColor; // 0x98
	private static DelegateBridge __Hotfix0_get_hideBattleColor; // 0xa0
	private static DelegateBridge __Hotfix0_get_hideEventColor; // 0xa8
	private static DelegateBridge __Hotfix0_get_hideBarBattleColor; // 0xb0
	private static DelegateBridge __Hotfix0_get_hideBarEventColor; // 0xb8
	private static DelegateBridge __Hotfix0_get_selectedTextColor; // 0xc0
	private static DelegateBridge __Hotfix0_get_unSelectedTextColor; // 0xc8
	private static DelegateBridge __Hotfix0_GetSelectableColor; // 0xd0
	private static DelegateBridge __Hotfix0_GetBottomBarColor; // 0xd8
	private static DelegateBridge __Hotfix0_GetIcon; // 0xe0
	private static DelegateBridge __Hotfix0_GetUnactiveIcon; // 0xe8
	private static DelegateBridge __Hotfix0_GetBackIcon; // 0xf0
	private static DelegateBridge __Hotfix0_GetNameIcon; // 0xf8
	private static DelegateBridge __Hotfix0_GetParticlePrefab; // 0x100
	private static DelegateBridge _c__Hotfix0_ctor; // 0x108

	public Color inactiveColor { get; }
	public Color activeColor { get; }
	public Color discardedColor { get; }
	public Color discardedLineColor { get; }
	public Color discardedVertLineColor { get; }
	public Color discardedReflectLineColor { get; }
	public Color discardedReflectArrowColor { get; }
	public Color discardedBkgColor { get; }
	public Color discardedIconColor { get; }
	public Color traceColor { get; }
	public Color traceBkgColor { get; }
	public Color traceIconColor { get; }
	public Color traceDefaultColor { get; }
	public Sprite bossIcon { get; }
	public Sprite finalBossIcon { get; }
	public Sprite lineImg { get; }
	public Sprite lineHiddenImg { get; }
	public Sprite lineLockedImg { get; }
	public Color vertLineDefaultColor { get; }
	public Color hideBattleColor { get; }
	public Color hideEventColor { get; }
	public Color hideBarBattleColor { get; }
	public Color hideBarEventColor { get; }
	public Color selectedTextColor { get; }
	public Color unSelectedTextColor { get; }

	// RVA: 0x2a00030 VA: 0x7595018030
	private Boolean ShouldSerializeunactiveSpriteData() { }
	// RVA: 0x2a00098 VA: 0x7595018098
	public Color get_inactiveColor() { }
	// RVA: 0x2a00100 VA: 0x7595018100
	public Color get_activeColor() { }
	// RVA: 0x2a00168 VA: 0x7595018168
	public Color get_discardedColor() { }
	// RVA: 0x2a001d0 VA: 0x75950181d0
	public Color get_discardedLineColor() { }
	// RVA: 0x2a00238 VA: 0x7595018238
	public Color get_discardedVertLineColor() { }
	// RVA: 0x2a002a0 VA: 0x75950182a0
	public Color get_discardedReflectLineColor() { }
	// RVA: 0x2a00308 VA: 0x7595018308
	public Color get_discardedReflectArrowColor() { }
	// RVA: 0x2a00370 VA: 0x7595018370
	public Color get_discardedBkgColor() { }
	// RVA: 0x2a003d8 VA: 0x75950183d8
	public Color get_discardedIconColor() { }
	// RVA: 0x2a00440 VA: 0x7595018440
	public Color get_traceColor() { }
	// RVA: 0x2a004a8 VA: 0x75950184a8
	public Color get_traceBkgColor() { }
	// RVA: 0x2a00510 VA: 0x7595018510
	public Color get_traceIconColor() { }
	// RVA: 0x2a00578 VA: 0x7595018578
	public Color get_traceDefaultColor() { }
	// RVA: 0x2a005e0 VA: 0x75950185e0
	public Sprite get_bossIcon() { }
	// RVA: 0x2a00648 VA: 0x7595018648
	public Sprite get_finalBossIcon() { }
	// RVA: 0x2a006b0 VA: 0x75950186b0
	public Sprite get_lineImg() { }
	// RVA: 0x2a00718 VA: 0x7595018718
	public Sprite get_lineHiddenImg() { }
	// RVA: 0x2a00780 VA: 0x7595018780
	public Sprite get_lineLockedImg() { }
	// RVA: 0x2a007e8 VA: 0x75950187e8
	public Color get_vertLineDefaultColor() { }
	// RVA: 0x2a00850 VA: 0x7595018850
	public Color get_hideBattleColor() { }
	// RVA: 0x2a008c0 VA: 0x75950188c0
	public Color get_hideEventColor() { }
	// RVA: 0x2a00930 VA: 0x7595018930
	public Color get_hideBarBattleColor() { }
	// RVA: 0x2a009a0 VA: 0x75950189a0
	public Color get_hideBarEventColor() { }
	// RVA: 0x2a00a10 VA: 0x7595018a10
	public Color get_selectedTextColor() { }
	// RVA: 0x2a00a80 VA: 0x7595018a80
	public Color get_unSelectedTextColor() { }
	// RVA: 0x2a00af0 VA: 0x7595018af0
	public Color GetSelectableColor(RoguelikeEventType type, Boolean isFinalBoss, PlayerNodeForesightType foresightType, Boolean isInTrace) { }
	// RVA: 0x2a00c8c VA: 0x7595018c8c
	public Color GetBottomBarColor(RoguelikeEventType type, Boolean isFinalBoss, PlayerNodeForesightType foresightType, Boolean isInTrace) { }
	// RVA: 0x2a00e28 VA: 0x7595018e28
	public Sprite GetIcon(RoguelikeEventType type, PlayerNodeForesightType foresightType, Boolean isInTrace) { }
	// RVA: 0x2a00f80 VA: 0x7595018f80
	public Sprite GetUnactiveIcon(RoguelikeEventType type) { }
	// RVA: 0x2a010ac VA: 0x75950190ac
	public Sprite GetBackIcon(RoguelikeEventType type) { }
	// RVA: 0x2a011d8 VA: 0x75950191d8
	public Sprite GetNameIcon(RoguelikeEventType type, PlayerNodeForesightType foresightType, Boolean isInTrace) { }
	// RVA: 0x2a01320 VA: 0x7595019320
	public GameObject GetParticlePrefab(RoguelikeEventType type, Boolean isFinalBoss, PlayerNodeForesightType foresightType) { }
	// RVA: 0x2a014c0 VA: 0x75950194c0
	public Void .ctor() { }
}
```