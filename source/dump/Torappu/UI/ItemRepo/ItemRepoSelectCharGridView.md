# ItemRepoSelectCharGridView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoSelectCharRowComp _rowComp`

- `Transform _viewContainer`

- `UIStateFinder m_stateFinder`

- `CommonSingleChooseCharGroupView m_groupView`

- `RenderParam m_renderParam`

- `GroupViewBuilder m_viewBuilder`


## Methods

- `Void Render(RenderParam)`

- `Void _PackRowViews(PackParams, List`1, ref)`

- `Void _OnCardClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoSelectCharGridView : MonoBehaviour, IHotfixable
{
	private const Int32 ROW_COUNT; // 0x0
	private ItemRepoSelectCharRowComp _rowComp; // 0x18
	private Transform _viewContainer; // 0x20
	private UIStateFinder m_stateFinder; // 0x28
	private CommonSingleChooseCharGroupView m_groupView; // 0x38
	private RenderParam m_renderParam; // 0x40
	private GroupViewBuilder m_viewBuilder; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__GenerateVirtualViews; // 0x8
	private static DelegateBridge __Hotfix0__GenerateDefaultVirtualViews; // 0x10
	private static DelegateBridge __Hotfix0__GenerateWithClassicVirtualViews; // 0x18
	private static DelegateBridge __Hotfix0__PackRowViews; // 0x20
	private static DelegateBridge __Hotfix0__OnCardClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2d38094 VA: 0x7595350094
	public Void Render(RenderParam renderParam) { }
	// RVA: 0x2d38314 VA: 0x7595350314
	private List`1 _GenerateVirtualViews() { }
	// RVA: 0x2d386c4 VA: 0x75953506c4
	private List`1 _GenerateDefaultVirtualViews(RenderParam renderParam) { }
	// RVA: 0x2d383e0 VA: 0x75953503e0
	private List`1 _GenerateWithClassicVirtualViews(RenderParam renderParam) { }
	// RVA: 0x2d388bc VA: 0x75953508bc
	private Void _PackRowViews(PackParams packParams, List`1 virtualViews, ref Boolean hasOwn) { }
	// RVA: 0x2d3917c VA: 0x759535117c
	private Void _OnCardClick(String charId) { }
	// RVA: 0x2d39288 VA: 0x7595351288
	public Void .ctor() { }
}
```