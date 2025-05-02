# SceneJoinRet

**Namespace:** ` `


## Fields

- `RetCode code`

- `Int64 nowTs`

- `Int64 createTs`

- `Int64 forceEndTs`

- `String newToken`

- `String stageID`

- `Int32 stageSeed`

- `Boolean reverse`


## Methods

- `UserInfo _InitSinglePlayer(NewPlayer)`

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SceneJoinRet : Protocol
{
	public const UInt32 ID; // 0x0
	public RetCode code; // 0x14
	public Int64 nowTs; // 0x18
	public Int64 createTs; // 0x20
	public Int64 forceEndTs; // 0x28
	public String newToken; // 0x30
	public String stageID; // 0x38
	public Int32 stageSeed; // 0x40
	public Boolean reverse; // 0x44
	public readonly ListDict`2 users; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__InitSinglePlayer; // 0x8
	private static DelegateBridge __Hotfix0_OnRead; // 0x10


	// RVA: 0x3597d94 VA: 0x7595bafd94
	public Void .ctor() { }
	// RVA: 0x3597e5c VA: 0x7595bafe5c
	private UserInfo _InitSinglePlayer(NewPlayer player) { }
	// RVA: 0x3598270 VA: 0x7595bb0270
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x3598744 VA: 0x7595bb0744
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```