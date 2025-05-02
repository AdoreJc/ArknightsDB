# ItemRepoCardGroupView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `UIIntEvent _cardClickEvent`

- `ItemRepoCardGroupAdapter _adapter`

- `GameObject _noItemImg`

- `ClassifyFilter m_cachedClass`


## Methods

- `Void _OnItemCardClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoCardGroupView : DataBinder`1, IHotfixable
{
	private UIIntEvent _cardClickEvent; // 0x20
	private ItemRepoCardGroupAdapter _adapter; // 0x28
	private GameObject _noItemImg; // 0x30
	private ClassifyFilter m_cachedClass; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__OnItemCardClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d2edcc VA: 0x7595346dcc
	public override Void OnValueChanged(ItemCardGroupViewProperty property) { }
	// RVA: 0x2d2f008 VA: 0x7595347008
	private Void _OnItemCardClick(Int32 position) { }
	// RVA: 0x2d2f0a8 VA: 0x75953470a8
	public Void .ctor() { }
}
```