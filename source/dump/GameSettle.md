# GameSettle

**Namespace:** ` `


## Fields

- `Int32 oprt`

- `UInt32 checkSum`

- `Int32 hp`

- `Int32 killCnt`

- `String resultInfo`

- `String battleStats`


## Methods

- `Void <>xLuaBaseProxy_OnWrite(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GameSettle : Protocol
{
	public const UInt32 ID; // 0x0
	public Int32 oprt; // 0x14
	public UInt32 checkSum; // 0x18
	public Int32 hp; // 0x1c
	public Int32 killCnt; // 0x20
	public String resultInfo; // 0x28
	public String battleStats; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnWrite; // 0x8


	// RVA: 0x359910c VA: 0x7595bb110c
	public Void .ctor() { }
	// RVA: 0x35991d0 VA: 0x7595bb11d0
	protected override Void OnWrite(IStreamWriter to) { }
	// RVA: 0x35994b8 VA: 0x7595bb14b8
	private Void <>xLuaBaseProxy_OnWrite(IStreamWriter P0) { }
}
```