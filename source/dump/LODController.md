# LODController

**Namespace:** ` `


## Fields

- `RL02OuterBuffController m_closure`

- `LOD m_lod`


## Methods

- `Void EventOnScaleChanged(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LODController : IHotfixable
{
	private RL02OuterBuffController m_closure; // 0x10
	private LOD m_lod; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_EventOnScaleChanged; // 0x8


	// RVA: 0x26baaac VA: 0x7594cd2aac
	public Void .ctor(RL02OuterBuffController closure) { }
	// RVA: 0x26bd4d0 VA: 0x7594cd54d0
	public Void EventOnScaleChanged(Single scale) { }
}
```