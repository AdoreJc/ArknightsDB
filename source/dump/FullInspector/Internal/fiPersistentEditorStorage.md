# fiPersistentEditorStorage

**Namespace:** `FullInspector.Internal`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Internal
public class fiPersistentEditorStorage
{
	private static Dictionary`2 _cachedRealComponentTypes; // 0x0
	private const String SceneStorageName; // 0x0
	private static GameObject _cachedSceneStorage; // 0x8
	private static String PrefabPath; // 0x10
	private static GameObject _cachedPrefabStorage; // 0x18

	public static GameObject SceneStorage { get; }
	public static GameObject PrefabStorage { get; }

	// RVA: 0x VA: 0x0
	public static Void Reset(fiUnityObjectReference key) { }
	// RVA: 0x VA: 0x0
	public static T Read(fiUnityObjectReference key) { }
	// RVA: 0x VA: 0x0
	private static fiBaseStorageComponent`1 GetStorageDictionary(GameObject container) { }
	// RVA: 0x34e6af0 VA: 0x7595afeaf0
	public static GameObject get_SceneStorage() { }
	// RVA: 0x34e6c5c VA: 0x7595afec5c
	public static GameObject get_PrefabStorage() { }
	// RVA: 0x34e6f00 VA: 0x7595afef00
	public Void .ctor() { }
	// RVA: 0x34e6f08 VA: 0x7595afef08
	private static Void .cctor() { }
}
```