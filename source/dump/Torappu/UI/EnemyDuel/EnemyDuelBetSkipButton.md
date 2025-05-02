# EnemyDuelBetSkipButton

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `UIAnimationLocation _animSelected`

- `Text _textSkip`

- `Color _textSkipColorNormal`

- `Color _textSkipColorMasked`

- `UIAtlasObject _atlasObject`

- `String _btnSkipSpriteNormal`

- `String _btnSkipSpriteMasked`

- `UIAtlasImage _imgBtn`

- `UISwitchTween m_selectedTween`

- `Boolean m_inited`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _InitIfNot()`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelBetSkipButton : AbstractEnemyDuelBetButton
{
	private UIAnimationLocation _animSelected; // 0x20
	private Text _textSkip; // 0x30
	private Color _textSkipColorNormal; // 0x38
	private Color _textSkipColorMasked; // 0x48
	private UIAtlasObject _atlasObject; // 0x58
	private String _btnSkipSpriteNormal; // 0x60
	private String _btnSkipSpriteMasked; // 0x68
	private UIAtlasImage _imgBtn; // 0x70
	private UISwitchTween m_selectedTween; // 0x78
	private Boolean m_inited; // 0x80
	private UIStateFinder m_stateFinder; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_SetSelected; // 0x8
	private static DelegateBridge __Hotfix0_OnClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x297c600 VA: 0x7594f94600
	private Void _InitIfNot() { }
	// RVA: 0x297c6f4 VA: 0x7594f946f4
	protected override Void SetSelected(ShowType showType, Boolean isInit) { }
	// RVA: 0x297c8e4 VA: 0x7594f948e4
	public Void OnClicked() { }
	// RVA: 0x297ca04 VA: 0x7594f94a04
	public Void .ctor() { }
}
```