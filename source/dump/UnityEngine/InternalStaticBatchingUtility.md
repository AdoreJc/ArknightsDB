# InternalStaticBatchingUtility

**Namespace:** `UnityEngine`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
internal class InternalStaticBatchingUtility
{


	// RVA: 0x688b9e8 VA: 0x7598ea39e8
	public static Void CombineRoot(GameObject staticBatchRoot, StaticBatcherGOSorter sorter) { }
	// RVA: 0x688bae4 VA: 0x7598ea3ae4
	public static Void Combine(GameObject staticBatchRoot, Boolean combineOnlyStatic, Boolean isEditorPostprocessScene, StaticBatcherGOSorter sorter) { }
	// RVA: 0x688d0d8 VA: 0x7598ea50d8
	private static UInt32 GetMeshFormatHash(Mesh mesh) { }
	// RVA: 0x688d1b4 VA: 0x7598ea51b4
	private static GameObject[] SortGameObjectsForStaticBatching(GameObject[] gos, StaticBatcherGOSorter sorter) { }
	// RVA: 0x688be5c VA: 0x7598ea3e5c
	public static Void CombineGameObjects(GameObject[] gos, GameObject staticBatchRoot, Boolean isEditorPostprocessScene, StaticBatcherGOSorter sorter) { }
	// RVA: 0x688d654 VA: 0x7598ea5654
	private static Void MakeBatch(List`1 meshes, Transform staticBatchRootTransform, Int32 batchIndex) { }
}
```