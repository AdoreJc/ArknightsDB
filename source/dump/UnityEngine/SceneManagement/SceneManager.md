# SceneManager

**Namespace:** `UnityEngine.SceneManagement`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.SceneManagement
public class SceneManager
{
	internal static Boolean s_AllowLoadScene; // 0x0
	private static UnityAction`2 sceneLoaded; // 0x8
	private static UnityAction`1 sceneUnloaded; // 0x10
	private static UnityAction`2 activeSceneChanged; // 0x18

	public static Int32 sceneCount { get; }

	// RVA: 0x68997cc VA: 0x7598eb17cc
	public static Int32 get_sceneCount() { }
	// RVA: 0x68997f4 VA: 0x7598eb17f4
	public static Scene GetActiveScene() { }
	// RVA: 0x68998ac VA: 0x7598eb18ac
	public static Scene GetSceneAt(Int32 index) { }
	// RVA: 0x689997c VA: 0x7598eb197c
	private static AsyncOperation LoadSceneAsyncNameIndexInternal(String sceneName, Int32 sceneBuildIndex, LoadSceneParameters parameters, Boolean mustCompleteNextFrame) { }
	// RVA: 0x6899a58 VA: 0x7598eb1a58
	private static AsyncOperation UnloadSceneNameIndexInternal(String sceneName, Int32 sceneBuildIndex, Boolean immediately, UnloadSceneOptions options, out Boolean outSuccess) { }
	// RVA: 0x6899b40 VA: 0x7598eb1b40
	internal static AsyncOperation LoadFirstScene_Internal(Boolean async) { }
	// RVA: 0x6899ba8 VA: 0x7598eb1ba8
	public static Void add_sceneLoaded(UnityAction`2 value) { }
	// RVA: 0x6899c9c VA: 0x7598eb1c9c
	public static Void remove_sceneLoaded(UnityAction`2 value) { }
	// RVA: 0x6899d90 VA: 0x7598eb1d90
	public static Void add_sceneUnloaded(UnityAction`1 value) { }
	// RVA: 0x6899e84 VA: 0x7598eb1e84
	public static Void remove_sceneUnloaded(UnityAction`1 value) { }
	// RVA: 0x6899f78 VA: 0x7598eb1f78
	public static Void add_activeSceneChanged(UnityAction`2 value) { }
	// RVA: 0x689a06c VA: 0x7598eb206c
	public static Void remove_activeSceneChanged(UnityAction`2 value) { }
	// RVA: 0x689a160 VA: 0x7598eb2160
	public static Void LoadScene(String sceneName, LoadSceneMode mode) { }
	// RVA: 0x689a270 VA: 0x7598eb2270
	public static Void LoadScene(String sceneName) { }
	// RVA: 0x689a1d0 VA: 0x7598eb21d0
	public static Scene LoadScene(String sceneName, LoadSceneParameters parameters) { }
	// RVA: 0x689a2c8 VA: 0x7598eb22c8
	public static Void LoadScene(Int32 sceneBuildIndex) { }
	// RVA: 0x689a320 VA: 0x7598eb2320
	public static Scene LoadScene(Int32 sceneBuildIndex, LoadSceneParameters parameters) { }
	// RVA: 0x689a3c0 VA: 0x7598eb23c0
	public static AsyncOperation LoadSceneAsync(String sceneName, LoadSceneMode mode) { }
	// RVA: 0x689a494 VA: 0x7598eb2494
	public static AsyncOperation LoadSceneAsync(String sceneName) { }
	// RVA: 0x689a428 VA: 0x7598eb2428
	public static AsyncOperation LoadSceneAsync(String sceneName, LoadSceneParameters parameters) { }
	// RVA: 0x689a4ec VA: 0x7598eb24ec
	public static AsyncOperation UnloadSceneAsync(String sceneName) { }
	// RVA: 0x689a560 VA: 0x7598eb2560
	private static Void Internal_SceneLoaded(Scene scene, LoadSceneMode mode) { }
	// RVA: 0x689a610 VA: 0x7598eb2610
	private static Void Internal_SceneUnloaded(Scene scene) { }
	// RVA: 0x689a6ac VA: 0x7598eb26ac
	private static Void Internal_ActiveSceneChanged(Scene previousActiveScene, Scene newActiveScene) { }
	// RVA: 0x689a75c VA: 0x7598eb275c
	private static Void .cctor() { }
	// RVA: 0x6899870 VA: 0x7598eb1870
	private static Void GetActiveScene_Injected(out Scene ret) { }
	// RVA: 0x6899938 VA: 0x7598eb1938
	private static Void GetSceneAt_Injected(Int32 index, out Scene ret) { }
}
```