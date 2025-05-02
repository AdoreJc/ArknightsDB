# MedalListAbleToGetItemView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Transform _itemCardContainer`

- `Text _name`

- `Image _icon`

- `Text _itemNameCount`

- `Single _scaler`

- `GameObject _itemRewardContainer`

- `UIMedalEvent clickMedalEvent`

- `MedalCommonViewModel m_viewModelCache`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void RenderView(MedalCommonViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalListAbleToGetItemView : MonoBehaviour, IHotfixable, IMedalListItem
{
	private Transform _itemCardContainer; // 0x18
	private Text _name; // 0x20
	private Image _icon; // 0x28
	private Text _itemNameCount; // 0x30
	private Single _scaler; // 0x38
	private GameObject _itemRewardContainer; // 0x40
	public UIMedalEvent clickMedalEvent; // 0x48
	private MedalCommonViewModel m_viewModelCache; // 0x50
	private UIItemCard m_itemCard; // 0x58
	private Boolean m_isInited; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x279fc70 VA: 0x7594db7c70
	private Void _InitIfNot() { }
	// RVA: 0x279fe04 VA: 0x7594db7e04
	public Void RenderView(MedalCommonViewModel viewModel) { }
	// RVA: 0x27a0100 VA: 0x7594db8100
	public Void OnClick() { }
	// RVA: 0x27a0198 VA: 0x7594db8198
	public Void .ctor() { }
}
```