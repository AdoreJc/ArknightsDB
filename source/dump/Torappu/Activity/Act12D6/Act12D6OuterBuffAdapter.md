# Act12D6OuterBuffAdapter

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `GameObject _outerBuffObj`

- `UIStringEvent _onOuterBuffDetailClicked`

- `UIStringEvent _onMaxLevelClicked`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6OuterBuffAdapter : RecycleLoopScrollAdapter`2, IHotfixable
{
	private GameObject _outerBuffObj; // 0x68
	private UIStringEvent _onOuterBuffDetailClicked; // 0x70
	private UIStringEvent _onMaxLevelClicked; // 0x78
	private static DelegateBridge __Hotfix0_UpdateView; // 0x0
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3476b54 VA: 0x7595a8eb54
	public override Void UpdateView(Int32 position, GameObject view, BuffObjViewHolder holder, RoguelikeOuterBuff data) { }
	// RVA: 0x3476ff8 VA: 0x7595a8eff8
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x34770b4 VA: 0x7595a8f0b4
	public Void .ctor() { }
}
```