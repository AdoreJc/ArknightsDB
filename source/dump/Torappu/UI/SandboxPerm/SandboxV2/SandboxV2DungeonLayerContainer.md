# SandboxV2DungeonLayerContainer

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DungeonController _controller`


## Methods

- `GameObject AttachObjectToLayer(SandboxV2DungeonLayerType, GameObject)`

- `TObject AttachObjectToLayer(SandboxV2DungeonLayerType, TObject)`

- `TObject AttachObjectToLayer(SandboxV2DungeonLayerType, TObject, Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonLayerContainer : MonoBehaviour, IHotfixable
{
	private List`1 _layerContainers; // 0x18
	private SandboxV2DungeonController _controller; // 0x20
	private static DelegateBridge __Hotfix0_AsyncAttachObjectToLayer; // 0x0
	private static DelegateBridge __Hotfix0_AttachObjectToLayer; // 0x8
	private static DelegateBridge __Hotfix1_AttachObjectToLayer; // 0x10
	private static DelegateBridge __Hotfix2_AttachObjectToLayer; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x VA: 0x0
	public AsyncDataViewHandler`2 AsyncAttachObjectToLayer(SandboxV2DungeonLayerType layer, TObject objPrefab, Int32 index, UInt32 singleCost) { }
	// RVA: 0x2570b14 VA: 0x7594b88b14
	public GameObject AttachObjectToLayer(SandboxV2DungeonLayerType layer, GameObject objPrefab) { }
	// RVA: 0x VA: 0x0
	public TObject AttachObjectToLayer(SandboxV2DungeonLayerType layer, TObject objPrefab) { }
	// RVA: 0x VA: 0x0
	public TObject AttachObjectToLayer(SandboxV2DungeonLayerType layer, TObject objPrefab, Vector2 pos) { }
	// RVA: 0x2570c74 VA: 0x7594b88c74
	public Void .ctor() { }
}
```