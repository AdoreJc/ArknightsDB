# MedalGroupListLoopAdapter

**Namespace:** `Torappu.UI.Medal`


## Fields

- `GameObject _itemObj`

- `UIStringEvent _onClickEvent`

- `UIPageListener m_pageListener`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalGroupListLoopAdapter : RecycleLoopScrollAdapter, IHotfixable
{
	public List`1 groupViewModelList; // 0x58
	private GameObject _itemObj; // 0x60
	private UIStringEvent _onClickEvent; // 0x68
	private UIPageListener m_pageListener; // 0x70
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x0
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 totalCount { get; }

	// RVA: 0x279dd58 VA: 0x7594db5d58
	public override Int32 get_totalCount() { }
	// RVA: 0x279ddd8 VA: 0x7594db5dd8
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x279dec8 VA: 0x7594db5ec8
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x279e054 VA: 0x7594db6054
	public Void .ctor() { }
}
```