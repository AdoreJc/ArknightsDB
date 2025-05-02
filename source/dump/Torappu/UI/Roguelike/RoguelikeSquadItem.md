# RoguelikeSquadItem

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Transform _cardContainer`

- `RoguelikeCharCommonCharView _charView`

- `GameObject _noCharPart`

- `GameObject _noPosPart`

- `AnimationWrapper _animationWrapper`

- `Int32 index`

- `UIIntEvent clickChar`

- `UIIntStringEvent clickCharSkill`

- `UIIntEvent clickPos`

- `RoguelikeCharCommonCharView m_charView`

- `Boolean m_isInited`


## Methods

- `Void OnClickPos()`

- `Void _InitIfNot()`

- `Void RenderNoChar(Boolean)`

- `Void RenderNoPos()`

- `Void RenderChar(RoguelikeCharCardViewModel)`

- `Void SetPlugins(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSquadItem : MonoBehaviour, IHotfixable
{
	private Transform _cardContainer; // 0x18
	private RoguelikeCharCommonCharView _charView; // 0x20
	private GameObject _noCharPart; // 0x28
	private GameObject _noPosPart; // 0x30
	private AnimationWrapper _animationWrapper; // 0x38
	public Int32 index; // 0x40
	public UIIntEvent clickChar; // 0x48
	public UIIntStringEvent clickCharSkill; // 0x50
	public UIIntEvent clickPos; // 0x58
	private RoguelikeCharCommonCharView m_charView; // 0x60
	private Boolean m_isInited; // 0x68
	private List`1 m_plugins; // 0x70
	private const String SHINING_ANIM_NAME; // 0x0
	private static DelegateBridge __Hotfix0_OnClickPos; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_RenderNoChar; // 0x10
	private static DelegateBridge __Hotfix0_RenderNoPos; // 0x18
	private static DelegateBridge __Hotfix0_RenderChar; // 0x20
	private static DelegateBridge __Hotfix0_SetPlugins; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2af831c VA: 0x759511031c
	public Void OnClickPos() { }
	// RVA: 0x2af83b0 VA: 0x75951103b0
	private Void _InitIfNot() { }
	// RVA: 0x2af84dc VA: 0x75951104dc
	public Void RenderNoChar(Boolean hasAvailChar) { }
	// RVA: 0x2af861c VA: 0x759511061c
	public Void RenderNoPos() { }
	// RVA: 0x2af86c4 VA: 0x75951106c4
	public Void RenderChar(RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2af87e8 VA: 0x75951107e8
	public Void SetPlugins(List`1 plugins) { }
	// RVA: 0x2af886c VA: 0x759511086c
	public Void .ctor() { }
}
```