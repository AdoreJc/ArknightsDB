# AIRLBridge

**Namespace:** `Torappu.AIRL`


## Fields

- `Boolean <inited>k__BackingField`

- `String <externLuaFolderPath>k__BackingField`

- `CustomLoader _customLoader`

- `String startLua`

- `String stopLua`

- `String levelJson`

- `String squadJson`

- `String runeJson`


## Properties

- `Boolean inited`

- `String externLuaFolderPath`


## Methods

- `Boolean get_inited()`

- `Void set_inited(Boolean)`

- `String get_externLuaFolderPath()`

- `Void set_externLuaFolderPath(String)`

- `Void Start(Options)`

- `Void DoLuaInit(String)`

- `Void Stop()`

- `Void DoLuaDispose()`

- `Void DoFixedUpdate()`

- `String _ConvertToFullPath(String)`

- `Void OnGameReset(BattleController)`

- `Void OnGameInit(Options)`

- `Void OnGameReady()`

- `Void OnGameStart()`

- `Void OnGameOver(GameResult)`

- `Void RestartGame(String, String, String)`

- `Object GetGameDataSample()`

- `UInt32 GetGameFixFrameCount()`

- `Void ManualFrameTick(Object)`

- `Void ManualFrameTickImp(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AIRL
public class AIRLBridge : Singleton`1, IBattleModule
{
	private Boolean <inited>k__BackingField; // 0x10
	private String <externLuaFolderPath>k__BackingField; // 0x18
	private CustomLoader _customLoader; // 0x20
	private const String DEFAULT_LUA_EXTENSION; // 0x0
	private String startLua; // 0x28
	private String stopLua; // 0x30
	public String levelJson; // 0x38
	public String squadJson; // 0x40
	public String runeJson; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_inited; // 0x8
	private static DelegateBridge __Hotfix0_set_inited; // 0x10
	private static DelegateBridge __Hotfix0_get_externLuaFolderPath; // 0x18
	private static DelegateBridge __Hotfix0_set_externLuaFolderPath; // 0x20
	private static DelegateBridge __Hotfix0_Start; // 0x28
	private static DelegateBridge __Hotfix0_DoLuaInit; // 0x30
	private static DelegateBridge __Hotfix0_Stop; // 0x38
	private static DelegateBridge __Hotfix0_DoLuaDispose; // 0x40
	private static DelegateBridge __Hotfix0_DoFixedUpdate; // 0x48
	private static DelegateBridge __Hotfix0__CustomLoader; // 0x50
	private static DelegateBridge __Hotfix0__ConvertToFullPath; // 0x58
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x60
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x68
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x70
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x78
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x80
	private static DelegateBridge __Hotfix0_RestartGame; // 0x88
	private static DelegateBridge __Hotfix0_GetGameDataSample; // 0x90
	private static DelegateBridge __Hotfix0_GetGameFixFrameCount; // 0x98
	private static DelegateBridge __Hotfix0_ManualFrameTick; // 0xa0
	private static DelegateBridge __Hotfix0_ManualFrameTickImp; // 0xa8

	public Boolean inited { get; set; }
	private String externLuaFolderPath { get; set; }

	// RVA: 0x3eee99c VA: 0x759650699c
	private Void .ctor() { }
	// RVA: 0x3eeea70 VA: 0x7596506a70
	public Boolean get_inited() { }
	// RVA: 0x3eeead8 VA: 0x7596506ad8
	private Void set_inited(Boolean value) { }
	// RVA: 0x3eeeb58 VA: 0x7596506b58
	private String get_externLuaFolderPath() { }
	// RVA: 0x3eeebc0 VA: 0x7596506bc0
	private Void set_externLuaFolderPath(String value) { }
	// RVA: 0x3eeec44 VA: 0x7596506c44
	public Void Start(Options options) { }
	// RVA: 0x3eeed74 VA: 0x7596506d74
	private Void DoLuaInit(String luaFilePath) { }
	// RVA: 0x3eeeecc VA: 0x7596506ecc
	public Void Stop() { }
	// RVA: 0x3eef06c VA: 0x759650706c
	private Void DoLuaDispose() { }
	// RVA: 0x3eef164 VA: 0x7596507164
	public Void DoFixedUpdate() { }
	// RVA: 0x3eef268 VA: 0x7596507268
	private Byte[] _CustomLoader(ref String filepath) { }
	// RVA: 0x3eef378 VA: 0x7596507378
	private String _ConvertToFullPath(String filepath) { }
	// RVA: 0x3eef474 VA: 0x7596507474
	public Void OnGameReset(BattleController controller) { }
	// RVA: 0x3eef590 VA: 0x7596507590
	public Void OnGameInit(Options levelOptions) { }
	// RVA: 0x3eef6ac VA: 0x75965076ac
	public Void OnGameReady() { }
	// RVA: 0x3eef7b0 VA: 0x75965077b0
	public Void OnGameStart() { }
	// RVA: 0x3eef8b4 VA: 0x75965078b4
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x3eef9e8 VA: 0x75965079e8
	public Void RestartGame(String levelJson, String squadJson, String runeJson) { }
	// RVA: 0x3eefc0c VA: 0x7596507c0c
	public Object GetGameDataSample() { }
	// RVA: 0x3eefc98 VA: 0x7596507c98
	public UInt32 GetGameFixFrameCount() { }
	// RVA: 0x3eefd24 VA: 0x7596507d24
	public Void ManualFrameTick(Object frame) { }
	// RVA: 0x3eefd9c VA: 0x7596507d9c
	private Void ManualFrameTickImp(List`1 frame) { }
}
```