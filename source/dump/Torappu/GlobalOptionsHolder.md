# GlobalOptionsHolder

**Namespace:** `Torappu`


## Fields

- `GlobalOptions _globalOptions`

- `DLogOptions _logOptions`

- `ResourceOptions _resourceOptions`

- `DBOptions _dbOptions`

- `AudioOptions _audioOptions`

- `NetworkOptions _networkOptions`

- `SDKOptions _sdkOptions`

- `LuaOptions _luaOptions`

- `BasicUIOptions _basicUIOptions`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class GlobalOptionsHolder : PersistentSingleton`1, ISingletonNotAutoCreate
{
	private GlobalOptions _globalOptions; // 0x18
	private DLogOptions _logOptions; // 0x20
	private ResourceOptions _resourceOptions; // 0x28
	private DBOptions _dbOptions; // 0x30
	private AudioOptions _audioOptions; // 0x38
	private NetworkOptions _networkOptions; // 0x40
	private SDKOptions _sdkOptions; // 0x48
	private LuaOptions _luaOptions; // 0x50
	private BasicUIOptions _basicUIOptions; // 0x58
	private static DelegateBridge __Hotfix0_OnDuplicated; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2f36760 VA: 0x759554e760
	protected override Void OnDuplicated() { }
	// RVA: 0x2f36820 VA: 0x759554e820
	public Void .ctor() { }
}
```