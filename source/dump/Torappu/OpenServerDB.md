# OpenServerDB

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class OpenServerDB : ConstTable`2
{
	private static DelegateBridge __Hotfix0_GetCurrentOpenServerData; // 0x0
	private static DelegateBridge __Hotfix0_GetCurrentOpenServerGroupData; // 0x8
	private static DelegateBridge __Hotfix0_get_returnData; // 0x10
	private static DelegateBridge __Hotfix0_get_returnV2Data; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public static ReturnData returnData { get; }
	public static ReturnV2Data returnV2Data { get; }

	// RVA: 0x31f3e78 VA: 0x759580be78
	public static OpenServerData GetCurrentOpenServerData() { }
	// RVA: 0x31f40bc VA: 0x759580c0bc
	public static OpenServerScheduleItem GetCurrentOpenServerGroupData() { }
	// RVA: 0x31f428c VA: 0x759580c28c
	public static ReturnData get_returnData() { }
	// RVA: 0x31f4310 VA: 0x759580c310
	public static ReturnV2Data get_returnV2Data() { }
	// RVA: 0x31f4394 VA: 0x759580c394
	public Void .ctor() { }
}
```