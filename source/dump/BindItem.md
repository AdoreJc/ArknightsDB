# BindItem

**Namespace:** ` `


## Fields

- `UIColorGraphic m_target`

- `Object m_refMark`


## Methods

- `Boolean IsInvalid()`

- `Void SetTarget(UIColorGraphic)`

- `Void AddGraphic(Graphic)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BindItem : IHotfixable
{
	private UIColorGraphic m_target; // 0x10
	private Object m_refMark; // 0x18
	private List`1 m_pendings; // 0x20
	private static DelegateBridge __Hotfix0_IsInvalid; // 0x0
	private static DelegateBridge __Hotfix0_SetTarget; // 0x8
	private static DelegateBridge __Hotfix0_AddGraphic; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fa0c28 VA: 0x75955b8c28
	public Boolean IsInvalid() { }
	// RVA: 0x2fa076c VA: 0x75955b876c
	public Void SetTarget(UIColorGraphic target) { }
	// RVA: 0x2fa09d4 VA: 0x75955b89d4
	public Void AddGraphic(Graphic graphic) { }
	// RVA: 0x2fa0b64 VA: 0x75955b8b64
	public Void .ctor() { }
}
```