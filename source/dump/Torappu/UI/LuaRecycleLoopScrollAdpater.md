# LuaRecycleLoopScrollAdpater

**Namespace:** `Torappu.UI`


## Fields

- `ILuaLayoutEvent m_event`


## Methods

- `Void BindLayoutEventListener(ILuaLayoutEvent)`

- `Void TraverseCtrlDefines(Action`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LuaRecycleLoopScrollAdpater : RecycleLoopScrollAdapter
{
	private ControllerDefine[] _ctrlDefines; // 0x58
	private ILuaLayoutEvent m_event; // 0x60
	private static DelegateBridge __Hotfix0_BindLayoutEventListener; // 0x0
	private static DelegateBridge __Hotfix0_TraverseCtrlDefines; // 0x8
	private static DelegateBridge __Hotfix0_get_totalCount; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Int32 totalCount { get; }

	// RVA: 0x22338fc VA: 0x759484b8fc
	public Void BindLayoutEventListener(ILuaLayoutEvent listener) { }
	// RVA: 0x2233980 VA: 0x759484b980
	public Void TraverseCtrlDefines(Action`2 traverse) { }
	// RVA: 0x2233a7c VA: 0x759484ba7c
	public override Int32 get_totalCount() { }
	// RVA: 0x2233b64 VA: 0x759484bb64
	protected override Void UpdateView(Transform transform, Int32 index) { }
	// RVA: 0x2233c6c VA: 0x759484bc6c
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x2233d70 VA: 0x759484bd70
	public Void .ctor() { }
}
```