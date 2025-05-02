# GamePlayerStatusRet

**Namespace:** ` `


## Fields

- `String uid`

- `BattlePlayerStatus status`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GamePlayerStatusRet : Protocol
{
	public const UInt32 ID; // 0x0
	public String uid; // 0x18
	public BattlePlayerStatus status; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x359bbcc VA: 0x7595bb3bcc
	public Void .ctor() { }
	// RVA: 0x359bc40 VA: 0x7595bb3c40
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x359bda4 VA: 0x7595bb3da4
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```