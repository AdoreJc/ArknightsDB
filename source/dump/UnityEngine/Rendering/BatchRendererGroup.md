# BatchRendererGroup

**Namespace:** `UnityEngine.Rendering`


## Fields

- `IntPtr m_GroupHandle`

- `OnPerformCulling m_PerformCulling`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine.Rendering
public class BatchRendererGroup
{
	private IntPtr m_GroupHandle; // 0x10
	private OnPerformCulling m_PerformCulling; // 0x18


	// RVA: 0x68a097c VA: 0x7598eb897c
	private static Void InvokeOnPerformCulling(BatchRendererGroup group, ref BatchRendererCullingOutput context, ref LODParameters lodParameters) { }
}
```