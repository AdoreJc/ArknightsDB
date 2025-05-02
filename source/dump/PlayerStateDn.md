# PlayerStateDn

**Namespace:** ` `


## Fields

- `String uid`

- `TeamMemberState state`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlayerStateDn : Protocol
{
	public const Int32 ID; // 0x0
	public String uid; // 0x18
	public TeamMemberState state; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x359fa60 VA: 0x7595bb7a60
	public Void .ctor() { }
	// RVA: 0x359fad4 VA: 0x7595bb7ad4
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x359fc38 VA: 0x7595bb7c38
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```