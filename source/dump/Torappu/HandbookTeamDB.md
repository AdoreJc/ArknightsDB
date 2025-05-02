# HandbookTeamDB

**Namespace:** `Torappu`


## Methods

- `Boolean TryGetTeamSort(String, out)`

- `Boolean IsTeamIconRaw(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class HandbookTeamDB : SimpleKVTable`2
{
	public const String DEFAULT_POWER_ID; // 0x0
	public const String RHODES_ID; // 0x0
	private static DelegateBridge __Hotfix0_TryGetTeamSort; // 0x0
	private static DelegateBridge __Hotfix0_IsTeamIconRaw; // 0x8
	private static DelegateBridge __Hotfix0_GetColor; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31f2a00 VA: 0x759580aa00
	public Boolean TryGetTeamSort(String powerId, out Int32 teamSort) { }
	// RVA: 0x31f2adc VA: 0x759580aadc
	public Boolean IsTeamIconRaw(String powerId) { }
	// RVA: 0x31f2ba4 VA: 0x759580aba4
	public static Color GetColor(String colorString) { }
	// RVA: 0x31f2c44 VA: 0x759580ac44
	public Void .ctor() { }
}
```