# RL04FragmentDetailCard

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `RL04FragmentItemCard _itemCard`

- `UIWrappedScrollRect _scrollRect`

- `ILoadAsset <loader>k__BackingField`

- `Boolean m_hasInited`


## Properties

- `ILoadAsset loader`


## Methods

- `ILoadAsset get_loader()`

- `Void set_loader(ILoadAsset)`

- `Void Render(IRoguelikeFragmentItemModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentDetailCard : MonoBehaviour, IHotfixable
{
	private RL04FragmentItemCard _itemCard; // 0x18
	private UIWrappedScrollRect _scrollRect; // 0x20
	private TitleConfig[] _titleConfigList; // 0x28
	private ILoadAsset <loader>k__BackingField; // 0x30
	private Boolean m_hasInited; // 0x38
	private static DelegateBridge __Hotfix0_get_loader; // 0x0
	private static DelegateBridge __Hotfix0_set_loader; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ILoadAsset loader { get; set; }

	// RVA: 0x2b1c6e8 VA: 0x75951346e8
	private ILoadAsset get_loader() { }
	// RVA: 0x2b1c750 VA: 0x7595134750
	public Void set_loader(ILoadAsset value) { }
	// RVA: 0x2b1c7d4 VA: 0x75951347d4
	public Void Render(IRoguelikeFragmentItemModel viewModel) { }
	// RVA: 0x2b1c970 VA: 0x7595134970
	private Void _InitIfNot() { }
	// RVA: 0x2b1ca1c VA: 0x7595134a1c
	public Void .ctor() { }
}
```