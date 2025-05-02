# Act12D6RelicHandBookGridAdapter

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `GameObject _relickObj`

- `UIStringEvent _onRelicClicked`

- `String chosenRelic`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6RelicHandBookGridAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private GameObject _relickObj; // 0x68
	private UIStringEvent _onRelicClicked; // 0x70
	public String chosenRelic; // 0x78
	private static DelegateBridge __Hotfix0_UpdateView; // 0x0
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x347801c VA: 0x7595a9001c
	public override Void UpdateView(Int32 position, GameObject view, RelicObjViewHolder holder, PlayerRelicHandBookData data) { }
	// RVA: 0x3478408 VA: 0x7595a90408
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x34784c4 VA: 0x7595a904c4
	public Void .ctor() { }
}
```