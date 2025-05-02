# UIBlockHandler

**Namespace:** ` `


## Fields

- `Int32 m_refCount`

- `UIPage m_page`

- `Int32 m_signature`


## Methods

- `Void Retain()`

- `Void Release()`

- `Int64 GetInstSignature()`

- `Void _OnRefActive()`

- `Void _OnRefInactive()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class UIBlockHandler : IRefCountInstance, IHotfixable
{
	private Int32 m_refCount; // 0x10
	private UIPage m_page; // 0x18
	private Int32 m_signature; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_Retain; // 0x8
	private static DelegateBridge __Hotfix0_Release; // 0x10
	private static DelegateBridge __Hotfix0_GetInstSignature; // 0x18
	private static DelegateBridge __Hotfix0__OnRefActive; // 0x20
	private static DelegateBridge __Hotfix0__OnRefInactive; // 0x28


	// RVA: 0x2157828 VA: 0x759476f828
	public Void .ctor(UIPage page) { }
	// RVA: 0x21578bc VA: 0x759476f8bc
	public Void Retain() { }
	// RVA: 0x2157a94 VA: 0x759476fa94
	public Void Release() { }
	// RVA: 0x2157cc0 VA: 0x759476fcc0
	public Int64 GetInstSignature() { }
	// RVA: 0x2157940 VA: 0x759476f940
	private Void _OnRefActive() { }
	// RVA: 0x2157b1c VA: 0x759476fb1c
	private Void _OnRefInactive() { }
}
```