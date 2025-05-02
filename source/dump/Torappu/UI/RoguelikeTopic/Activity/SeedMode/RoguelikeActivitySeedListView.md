# RoguelikeActivitySeedListView

**Namespace:** `Torappu.UI.RoguelikeTopic.Activity.SeedMode`


## Fields

- `SimpleLayoutContent _itemContent`

- `CanvasGroup _itemGroup`

- `Single _fadeDuration`

- `GameObject _tipsHistory`

- `GameObject _tipsPredefine`

- `SeedListAdapter m_adapter`

- `Boolean m_isInited`

- `RoguelikeActivitySeedListModel m_cachedModel`

- `Int32 m_switchTagSequenceNum`

- `Sequence m_switchSequence`

- `ILoadAsset m_iLoadAsset`


## Methods

- `Void Render(RoguelikeActivitySeedListModel, ILoadAsset)`

- `Void _Render(RoguelikeActivitySeedListModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Activity.SeedMode
public class RoguelikeActivitySeedListView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _itemContent; // 0x18
	private CanvasGroup _itemGroup; // 0x20
	private Single _fadeDuration; // 0x28
	private List`1 _seedTypeTags; // 0x30
	private GameObject _tipsHistory; // 0x38
	private GameObject _tipsPredefine; // 0x40
	private SeedListAdapter m_adapter; // 0x48
	private Boolean m_isInited; // 0x50
	private RoguelikeActivitySeedListModel m_cachedModel; // 0x58
	private Int32 m_switchTagSequenceNum; // 0x60
	private Sequence m_switchSequence; // 0x68
	private ILoadAsset m_iLoadAsset; // 0x70
	public Action`1 onClickSwitchTag; // 0x78
	public Action`1 onClickSelectSeed; // 0x80
	public Action`1 onClickCopySeed; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x26e0f2c VA: 0x7594cf8f2c
	public Void Render(RoguelikeActivitySeedListModel model, ILoadAsset iLoadAsset) { }
	// RVA: 0x26e397c VA: 0x7594cfb97c
	private Void _Render(RoguelikeActivitySeedListModel model) { }
	// RVA: 0x26e3830 VA: 0x7594cfb830
	private Void _InitIfNot() { }
	// RVA: 0x26e3b68 VA: 0x7594cfbb68
	public Void .ctor() { }
}
```