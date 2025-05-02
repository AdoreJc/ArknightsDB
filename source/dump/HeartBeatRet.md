# HeartBeatRet

**Namespace:** ` `


## Fields

- `UInt32 seq`

- `Int64 time`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HeartBeatRet : Protocol
{
	public const UInt32 ID; // 0x0
	public UInt32 seq; // 0x14
	public Int64 time; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x3575d84 VA: 0x7595b8dd84
	public Void .ctor() { }
	// RVA: 0x3575df4 VA: 0x7595b8ddf4
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x3575f48 VA: 0x7595b8df48
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```