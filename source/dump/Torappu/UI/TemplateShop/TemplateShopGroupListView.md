# TemplateShopGroupListView

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `UIRecycleHorizonLayoutGroup _recycleList`

- `TemplateShopLoopGroupView _groupView`

- `AsyncGameObjectLoader objLoader`

- `TemplateShopGroupLoopAdapter m_loopAdapter`

- `ScrollRect _scrollRect`

- `Int32 m_constraintCount`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Int32 CalcConstraint()`

- `Void FocusOnIndex(Int32)`

- `Void Render(List`1, TemplateShopResHolder)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopGroupListView : MonoBehaviour, IHotfixable
{
	private static readonly Vector2 CELL_SIZE; // 0x0
	private static readonly Vector2 SPACING; // 0x8
	private UIRecycleHorizonLayoutGroup _recycleList; // 0x18
	private TemplateShopLoopGroupView _groupView; // 0x20
	public AsyncGameObjectLoader objLoader; // 0x28
	private TemplateShopGroupLoopAdapter m_loopAdapter; // 0x30
	private ScrollRect _scrollRect; // 0x38
	private Int32 m_constraintCount; // 0x40
	private Boolean m_isInited; // 0x44
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_CalcConstraint; // 0x18
	private static DelegateBridge __Hotfix0_FocusOnIndex; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x235d14c VA: 0x759497514c
	public Void _InitIfNot() { }
	// RVA: 0x235d2b0 VA: 0x75949752b0
	private Int32 CalcConstraint() { }
	// RVA: 0x2356124 VA: 0x759496e124
	public Void FocusOnIndex(Int32 itemIndex) { }
	// RVA: 0x23550b0 VA: 0x759496d0b0
	public Void Render(List`1 viewModelList, TemplateShopResHolder resHolder) { }
	// RVA: 0x235d4b0 VA: 0x75949754b0
	public Void .ctor() { }
	// RVA: 0x235d530 VA: 0x7594975530
	private static Void .cctor() { }
}
```