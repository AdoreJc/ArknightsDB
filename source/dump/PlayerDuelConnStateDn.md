# PlayerDuelConnStateDn

**Namespace:** ` `


## Fields

- `String uid`

- `Boolean shouldDelete`

- `Boolean connLeave`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PlayerDuelConnStateDn : Protocol
{
	public const Int32 ID; // 0x0
	public String uid; // 0x18
	public Boolean shouldDelete; // 0x20
	public Boolean connLeave; // 0x21
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x29b5498 VA: 0x7594fcd498
	public Void .ctor() { }
	// RVA: 0x29b550c VA: 0x7594fcd50c
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x29b56cc VA: 0x7594fcd6cc
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```