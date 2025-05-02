# SceneManagerAPI

**Namespace:** `UnityEngine.SceneManagement`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.SceneManagement
public class SceneManagerAPI
{
	private static SceneManagerAPI s_DefaultAPI; // 0x0
	private static SceneManagerAPI <overrideAPI>k__BackingField; // 0x8

	internal static SceneManagerAPI ActiveAPI { get; }
	public static SceneManagerAPI overrideAPI { get; }

	// RVA: 0x6899580 VA: 0x7598eb1580
	internal static SceneManagerAPI get_ActiveAPI() { }
	// RVA: 0x6899628 VA: 0x7598eb1628
	public static SceneManagerAPI get_overrideAPI() { }
	// RVA: 0x6899680 VA: 0x7598eb1680
	protected internal Void .ctor() { }
	// RVA: 0x6899688 VA: 0x7598eb1688
	protected internal virtual AsyncOperation LoadSceneAsyncByNameOrIndex(String sceneName, Int32 sceneBuildIndex, LoadSceneParameters parameters, Boolean mustCompleteNextFrame) { }
	// RVA: 0x68996e8 VA: 0x7598eb16e8
	protected internal virtual AsyncOperation UnloadSceneAsyncByNameOrIndex(String sceneName, Int32 sceneBuildIndex, Boolean immediately, UnloadSceneOptions options, out Boolean outSuccess) { }
	// RVA: 0x6899754 VA: 0x7598eb1754
	protected internal virtual AsyncOperation LoadFirstScene(Boolean mustLoadAsync) { }
	// RVA: 0x689975c VA: 0x7598eb175c
	private static Void .cctor() { }
}
```