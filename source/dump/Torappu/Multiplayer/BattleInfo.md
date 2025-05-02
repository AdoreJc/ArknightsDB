# BattleInfo

**Namespace:** `Torappu.Multiplayer`


## Fields

- `Int64 createTs`

- `Int64 forceEndTs`

- `String actStageID`

- `Int32 randomSeed`

- `Boolean reverse`

- `Int32 fail`

- `String sceneID`

- `Boolean started`


## Properties

- `Boolean valid`


## Methods

- `Boolean get_valid()`

- `Void Reset()`

- `Void CopyFrom(SceneJoinRet)`

- `BattlePlayerStatus GetLastStatus(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class BattleInfo
{
	public static Nullable`1 s_latestSettle; // 0x0
	public Int64 createTs; // 0x10
	public Int64 forceEndTs; // 0x18
	public String actStageID; // 0x20
	public Int32 randomSeed; // 0x28
	public Boolean reverse; // 0x2c
	public Int32 fail; // 0x30
	public List`1 players; // 0x38
	public String sceneID; // 0x40
	public Boolean started; // 0x48
	public ListDict`2 lastStatus; // 0x50

	public Boolean valid { get; }

	// RVA: 0x358bba0 VA: 0x7595ba3ba0
	public Boolean get_valid() { }
	// RVA: 0x358bbc0 VA: 0x7595ba3bc0
	public Void Reset() { }
	// RVA: 0x358bcb0 VA: 0x7595ba3cb0
	public Void CopyFrom(SceneJoinRet ret) { }
	// RVA: 0x358bfe4 VA: 0x7595ba3fe4
	public BattlePlayerStatus GetLastStatus(String uid) { }
	// RVA: 0x358c058 VA: 0x7595ba4058
	public Void .ctor() { }
}
```