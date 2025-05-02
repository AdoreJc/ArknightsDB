# HGGameUpdateCallback

**Namespace:** `Hypergryph.SDK`


## Methods

- `Void onLatestGame(String)`

- `Void runInMainTread(Action)`


## Dump
```C#
// Dll : Hypergryph.GameUpdate.dll
// Namespace : Hypergryph.SDK
public class HGGameUpdateCallback : MonoBehaviour
{
	private static IHGGameUpdateSDKCallback m_callback; // 0x0
	private const String gameObjectName; // 0x0
	private static SynchronizationContext mainThreadContext; // 0x8
	public static HGGameUpdateCallback s_instance; // 0x10


	// RVA: 0x5ebf004 VA: 0x75984d7004
	public Void .ctor() { }
	// RVA: 0x5ebf06c VA: 0x75984d706c
	public static Void Init(IHGGameUpdateSDKCallback callback) { }
	// RVA: 0x5ebf248 VA: 0x75984d7248
	public Void onLatestGame(String data) { }
	// RVA: 0x5ebf308 VA: 0x75984d7308
	private Void runInMainTread(Action action) { }
}
```