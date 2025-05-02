# UIImageOnPopulateMesh

**Namespace:** `Torappu.Battle.UI`


## Methods

- `Void add_onPopulateMesh(Action`1)`

- `Void remove_onPopulateMesh(Action`1)`

- `Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIImageOnPopulateMesh : Image, IHotfixable
{
	private Action`1 onPopulateMesh; // 0x188
	private static DelegateBridge __Hotfix0_add_onPopulateMesh; // 0x0
	private static DelegateBridge __Hotfix0_remove_onPopulateMesh; // 0x8
	private static DelegateBridge __Hotfix0_OnPopulateMesh; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x207bfb0 VA: 0x7594693fb0
	public Void add_onPopulateMesh(Action`1 value) { }
	// RVA: 0x20804dc VA: 0x75946984dc
	public Void remove_onPopulateMesh(Action`1 value) { }
	// RVA: 0x20805d4 VA: 0x75946985d4
	protected override Void OnPopulateMesh(VertexHelper toFill) { }
	// RVA: 0x2080684 VA: 0x7594698684
	public Void .ctor() { }
	// RVA: 0x2080718 VA: 0x7594698718
	private Void <>xLuaBaseProxy_OnPopulateMesh(VertexHelper P0) { }
}
```