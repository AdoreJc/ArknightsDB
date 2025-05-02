# TeamJoinRet

**Namespace:** ` `


## Fields

- `RetCode retCode`

- `String reason`

- `Int64 svrTime`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TeamJoinRet : Protocol
{
	public const UInt32 ID; // 0x0
	public RetCode retCode; // 0x14
	public String reason; // 0x18
	public Int64 svrTime; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x359cb28 VA: 0x7595bb4b28
	public Void .ctor() { }
	// RVA: 0x359cb9c VA: 0x7595bb4b9c
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x359cd5c VA: 0x7595bb4d5c
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```