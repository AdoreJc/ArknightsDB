# GamePauseRet

**Namespace:** ` `


## Fields

- `String uid`

- `GamePauseParam opr`


## Methods

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GamePauseRet : Protocol
{
	public const UInt32 ID; // 0x0
	public String uid; // 0x18
	public GamePauseParam opr; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnRead; // 0x8


	// RVA: 0x359b978 VA: 0x7595bb3978
	public Void .ctor() { }
	// RVA: 0x359b9ec VA: 0x7595bb39ec
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x359bb50 VA: 0x7595bb3b50
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```