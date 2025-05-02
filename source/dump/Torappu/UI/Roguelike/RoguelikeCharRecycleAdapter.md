# RoguelikeCharRecycleAdapter

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeCommonCharHolder _holderPrefab`

- `UIIntEvent _charClick`

- `UIIntStringEvent _charSkillClick`

- `UInt32 _asyncCostPerFrame`

- `ShowConfig showConfig`

- `Boolean isSingle`

- `AsyncGameObjectLoader m_viewLoader`


## Methods

- `Int32 _GetSelectInstIndex(Int32)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharRecycleAdapter : LoopScrollAdapter`2
{
	private RoguelikeCommonCharHolder _holderPrefab; // 0x58
	private UIIntEvent _charClick; // 0x60
	private UIIntStringEvent _charSkillClick; // 0x68
	private UInt32 _asyncCostPerFrame; // 0x70
	public List`1 selectInstIdList; // 0x78
	public ShowConfig showConfig; // 0x80
	public Boolean isSingle; // 0x82
	public List`1 plugins; // 0x88
	private AsyncGameObjectLoader m_viewLoader; // 0x90
	private static DelegateBridge __Hotfix0__GetSelectInstIndex; // 0x0
	private static DelegateBridge __Hotfix0_CreateView; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2acb7d8 VA: 0x75950e37d8
	private Int32 _GetSelectInstIndex(Int32 instId) { }
	// RVA: 0x2acb8c8 VA: 0x75950e38c8
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2acb998 VA: 0x75950e3998
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, RoguelikeCharCardViewModel data) { }
	// RVA: 0x2acbe38 VA: 0x75950e3e38
	private Void Update() { }
	// RVA: 0x2acbeb4 VA: 0x75950e3eb4
	public Void .ctor() { }
}
```