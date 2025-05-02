# Act9D0NewsGroupAdapter

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `GameObject _newsObjPrefab`

- `UIStringEvent _onNewsObjClicked`

- `String cachedNewsChosenId`

- `String cachedActId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0NewsGroupAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private GameObject _newsObjPrefab; // 0x68
	private UIStringEvent _onNewsObjClicked; // 0x70
	public String cachedNewsChosenId; // 0x78
	public String cachedActId; // 0x80
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x31a8ec8 VA: 0x75957c0ec8
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x31a8f84 VA: 0x75957c0f84
	public override Void UpdateView(Int32 position, GameObject view, NewsObjViewHolder holder, Act9D0NewsViewModel data) { }
	// RVA: 0x31a93c4 VA: 0x75957c13c4
	public Void .ctor() { }
}
```